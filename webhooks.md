
## Existing solutions

The are some gems created to handle webhooks from specific services:

### Stripe

  - [stripe_event](https://github.com/integrallis/stripe_event)

### GitHub

  - [github_webhook](https://github.com/ssaunier/github_webhook)


## Tutorials

- [Handling stripe webhooks with Ruby on Rails](https://dev.to/maxencehenneron/handling-stripe-webhooks-with-ruby-on-rails-4bb7) by Maxence Henneron   (26 Mar 2019)
- Screencast: [Stripe Signed Webhooks](https://gorails.com/episodes/stripe-signed-webhooks) by GoRails (22 August 2018)
- [Efficent webhook handling with Ruby on Rails](https://dev.to/arandilopez/efficent-webhook-handlig-with-ruby-on-rails-4pj) by  Arandi López  (3 Jun  2018)
- [Setting up a Stripe webhook in Rails](http://www.bentedder.com/setting-up-a-stripe-webhook-in-rails/) by Ben Tedder (11 May 2017)


## Real life examples

- Rubytoolbox [uses github_webhook](https://github.com/rubytoolbox/rubytoolbox/blob/master/app/controllers/webhooks/github_controller.rb)

- Dev.to handles webhook from Twitch:
  - https://github.com/thepracticaldev/dev.to/blob/24328417ab49a1cc253b5d82df9aa6218028d168/app/services/streams/twitch_webhook/register.rb
  - https://github.com/thepracticaldev/dev.to/blob/ec388804df474eb7444f0204876b50c3dc867d17/app/jobs/streams/twitch_webhook_registration_job.rb
  - https://github.com/thepracticaldev/dev.to/blob/52c60ce37e415dbe71377b26af8124bbeeb2c043/app/controllers/users_controller.rb#L44

- OpenProject [handles GitHub webhooks manually](https://github.com/opf/openproject/blob/550c87a0791d66fc33503a9c4ccbdf9c0dce7a3d/modules/github_integration/lib/open_project/github_integration/hook_handler.rb)

- Dabble.me [processes Paypal, PayHere and Gumroad webhooks](https://github.com/parterburn/dabble.me/blob/bfab96a9074d5c71c45a98f35652a732ad633f38/app/controllers/payments_controller.rb)


## Useful links

- [Ultrahook](http://www.ultrahook.com) redirects webhooks to localhost
- [Ngrok](https://ngrok.com/) exposes your local app on a public URL