# Drupal 8 Development & Maintenance Workflows

## Abstract

High: Increase Drupal 8 app development and maintence productivity and satisfaction.

Medium: Level up development and maintenance workflows. Currently working directly on prod environments. This is not optimal. If somethign happend to app then we are in trouble; there's all the issue with "DRY" (Don't repeat Yourself.)

Low: Create written documentation on "How we build and maintain Drupal 8 apps."

Assumptions:

### Philosopy

- As few moving parts as possible
- As few processes as possible
- As few technologies as possible
- Always use lower level tools and techniques when possible

### Team

- devs
  - junior
  - senior
    - can access prod servers
    - can push to prod environments
- content authors
- site builders
- themers

### Environments

- dev (dev would happen on local machine - normally; but for your experiment well use Cloudways for all 3 environemtns)
- stage
- prod

### Technologies

- git
- drush
- drupal console (console)
- composer create-project drupal-composer/drupal-project:8.x-dev drupal --stability dev --no-interaction for base
- ssh
- sftp

### Techniques:

- configuration split
- use installation profile in conjunction with config sync

### Vendors

- GitHub
- Cloudways (for dev and stage environemts)

### Tools:

- Workflowy
- Evernote
- Dropbox

Resources:

- 