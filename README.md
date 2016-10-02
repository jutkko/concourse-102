# concourse-102
After failing to set up concourse with docker, I decided to go with the more
traditional way of deploying concourse using vagrant. Simple steps to do that

- Install [vagrant](https://www.vagrantup.com/)
- Install one of the virtual machine technologies vagrant supports, in my case
  [virtualbox](https://www.virtualbox.org/)
- Clone concourse/lite from [github](https://github.com/concourse/concourse-lite)
- `vagrant up`

## concourse-tutorial from Stark & Wayne
It is the most complete, most explained tutorial for concourse, period. So you
better clone that.

- `git clone https://github.com/starkandwayne/concourse-tutorial`

Start!

Watch [Alex's](https://github.com/vito) video
[here](https://www.youtube.com/watch?v=mYTn3qBxPhQ&list=WL&index=27), and then
read the summary from Stark & Wayne [here](https://github.com/starkandwayne/concourse-tutorial/blob/master/docs/alex-suraci-cfsummit-2015.md)

The first three tasks are using `fly execute`. They give you a basic
understanding of how to run a job from your directory.

The later on tasks are for configuring a pipeline, the real tofu (I don't eat
meat) starts here.

The resources are checked every minute, so let be more patient.

# Reference
[Tutorial](https://github.com/starkandwayne/concourse-tutorial) from Stark &
Wayne

# Project52
This is a project from my [Project52](https://github.com/jutkko/project52).
