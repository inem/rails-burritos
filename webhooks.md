
## Common way to do it

The are some gems created to handle webhooks from specific services:

Stripe
  - [stripe_event](https://github.com/integrallis/stripe_event)
  - [webhook-gem](https://github.com/digidem/webhook-gem)

GitHub

- [github_webhook](https://github.com/ssaunier/github_webhook)



## Tutorials

- [Handling stripe webhooks with Ruby on Rails](https://dev.to/maxencehenneron/handling-stripe-webhooks-with-ruby-on-rails-4bb7) by Maxence Henneron   (26 Mar 2019)
- Screencast: [Stripe Signed Webhooks](https://gorails.com/episodes/stripe-signed-webhooks) by GoRails (22 August 2018)
- [Efficent webhook handling with Ruby on Rails](https://dev.to/arandilopez/efficent-webhook-handlig-with-ruby-on-rails-4pj) by  Arandi López  (3 Jun  2018)
- [Setting up a Stripe webhook in Rails](http://www.bentedder.com/setting-up-a-stripe-webhook-in-rails/) by Ben Tedder (11 May 2017)


## Real life examples

- Rubytoolbox [uses github_webhook](https://github.com/rubytoolbox/rubytoolbox/blob/master/app/controllers/webhooks/github_controller.rb)


## Useful links

- [Ultrahook](http://www.ultrahook.com) redirects webhooks to localhost
- [Ngrok](https://ngrok.com/) exposes your local app on a public URL