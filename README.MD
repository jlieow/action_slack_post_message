Sends a message to a Channel via the slack chat.postMessage API.

```
- name: Informs Slack user that workflow has started
  id: slack_message
  uses: jlieow/slack_post_message@V1 # Uses an action in the repo terraformx_apply owned by jlieow tagged as V1
  with:
    slack_bot_user_oauth_token: xoxo-
    slack_channel_id: 1234
    message: "Hello World"
```
