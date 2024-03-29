# Webhooks handling


## Existing solutions

The are some gems created to handle webhooks from specific services:

### Stripe

  - [stripe_event](https://github.com/integrallis/stripe_event)
  - [stripe_model_callbacks](https://github.com/kaspernj/stripe_model_callbacks)

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

- Octobox [handles GitHub webhooks](https://github.com/octobox/octobox/blob/e6696555fce94fc429f2cee83920090ff88dde2c/app/controllers/hooks_controller.rb)
  - https://github.com/octobox/octobox/blob/e593cd64ddfba417036da956fa30f0ee11298891/app/workers/marketplace_purchase_worker.rb

- Dav (Stripe webhooks):
  - https://github.com/dav-apps/rails-backend/blob/25962d127a7a67e6c2d2e12cd394a55bc39d988b/app/services/stripe_webhooks_service.rb
  - https://github.com/dav-apps/rails-backend/blob/25962d127a7a67e6c2d2e12cd394a55bc39d988b/config/initializers/stripe.rb

- Mailchimp webhooks handling:
  - https://github.com/elm-city-craftworks/practicing-ruby-web/blob/751630511b74502eec66d2722aba55897ccadf3a/lib/mail_chimp/web_hooks.rb

- RubyTogether uses stripe_event:
  - https://github.com/rubytogether/rubytogether.org/tree/main/app/lib/stripe_event

- Mergehook uses github_webhook:
  - https://github.com/ssaunier/mergehook/blob/master/app/controllers/github_webhooks_controller.rb

- Thoughtbot's Upcase (Intercom webhook):
  - https://github.com/thoughtbot/upcase/blob/master/app/controllers/webhooks/intercom_unsubscribes_controller.rb

- Stripe webhooks jandling with stripe_event:
  - https://github.com/careeer/app-careeer/tree/master/app/models/webhooks

- Another github_webhook usage:
  https://github.com/Schwarzenegger/OctoEvents/blob/master/app/controllers/github_webhooks_controller.rb

## Useful links

- [Ultrahook](http://www.ultrahook.com) redirects webhooks to localhost
- [Ngrok](https://ngrok.com/) exposes your local app on a public URL


## Related

