# MadeTech R&D design system

Common design system for the staff-facing/back-office interfaces of MT R&D projects.

Consumes and augments [GOV.UK frontend](https://frontend.design-system.service.gov.uk/).

## Developing with it locally

You have two choices:

- Build any new components in your consumer app, and once happy, move the code "upstream" into this design system and publish a new version of it to npm.
- Use [npm link](https://docs.npmjs.com/cli/v6/commands/npm-link)

npm link is a cleaner way to work because the design system gets updates _immediately_—no pottering around with removing code from your consumer app later. To use it:

1. Clone this rep
2. Run `npm link` from the directory
3. In your consumer app, run `npm link rnd-design-system`

Changes you make to the local copy will be reflected immediately in your consumer app. No need to push new npm versions!
