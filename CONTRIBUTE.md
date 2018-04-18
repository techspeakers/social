# @TechSpeakers Content Queue
## The concept
This repository serves as a curation tool for the [@mozTechSpeakers](https://twitter.com/mozTechSpeakers) Twitter account. Each issue represents a Tweet or Retweet on that account. The issue gets validated by a service, if it is tweetable. If it is deemed ready and the curators of the Twitter account accept the content it will eventually be tweeted. This allows any user with a GitHub account to suggest content for the Twitter account while still retaining control over what is actually tweeted. Further it simplifies letting multiple users tweet from a single account.

## How to submit a tweet
### Open an issue
To suggest tweet content, open an issue in this repository and fill out the issue template. The issue will be added to the "Ideas" column on our project board.

Tweets should be English. You can attach images by uploading them to the issue and embedding them using the GitHub image syntax in the tweet content.

A tweet does not need to be scheduled to a specific time. Please only schedule it to a specific time if the content is time-sensitive, like event notices or campaigns.

To reply to a tweet add a `## Reply to` section to the issues and paste the link to the tweet to reply to as its content. Example:
```md
## Reply to
https://twitter.com/MozillaCH/status/917786667259482124
```

The template suggests a normal tweet by default, but you can also retweet a tweet by changing the `## Tweet Content` heading to `## Retweet` and pasting a link to the tweet to retweet as its contents. Example:
```md
## Retweet
https://twitter.com/MozillaCH/status/917786667259482124
```

### Ensure content is ready
The service will assign the "ready" label, once your tweet satisfies the formating restrictions of the service and its contents will be tweetable. It will report any outstanding issues else.

### Getting tweeted
Curators will now review the content. Once that is done and potential spelling mistakes are fixed, the issue will be moved to "To Tweet" by a curator where it will be tweeted.

## Contribution guidelines
If the tweet content is changed last-minute after the tweet is approved for reasons that weren't discussed in the issue, we may exclude you in the future from submitting tweets.

The [Mozilla Community Participation Guidelines](https://www.mozilla.org/en-US/about/governance/policies/participation/) apply.

## Curators
Curators are contributors who have write access to the repository. It's up to the TechSpeaker program to define who can be a curator.

### Being a curator
Curators should not move issues with tweet content they created through the board. Curators should self-assign themselves to an issue if they are handling its movements through a board and are coaching the contributor that is authoring a tweet.
