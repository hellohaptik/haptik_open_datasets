# Smalltalk Classification Dataset

This dataset contains a small subset of user messages sent to bots on Haptik platform. It can be used to build a system that can classify a given message as [chit-chat/smalltalk](https://en.wikipedia.org/wiki/Small_talk) or not. Messages that are not focused on getting some task done by the bot can be termed as chit-chat. Messages in this dataset were manually annotated by human agents.

---

`train.csv` has three columns

- `uid`  - unique id for the data point
- `message` - the body of the message
- `label` - `1` or `0` where `1` means the message is chit-chat type and `0` means it is not.

`test.csv` has same columns as `train.csv` except the `label` column

---

There are total `182,234` train instances and `78,276` test instances.

----

Note: numbers, emails, urls and other sensitive information has been replaced with generic tags like `_number_`, `_email_`, `_url_`, and so on.