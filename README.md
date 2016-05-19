# CodedeploySlackNotify

## Installation

Add this line to your application's Gemfile:

```ruby
gem 'codedeploy_slack_notify'
```

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install codedeploy_slack_notify

## Usage

```sh
$ SLACK_WEBHOOK_URL="https://hooks.slack.com/services/xxxxxxxxx/xxxxxxxxx/xxxxxxxxxxxxxxxxxxxxxxxx" \
SLACK_CHANNEL="#xxxxxxxxxxx" \
SLACK_USERNAME=xxxxxxxxxxxxxxxx \
DEPLOYMENT_ID=d-xxxxxxx \
codedeploy_slack_notify
```

## Note

Supports only "Deployment Config: `CodeDeployDefault.OneAtATime`"

## License

The gem is available as open source under the terms of the [MIT License](http://opensource.org/licenses/MIT).

