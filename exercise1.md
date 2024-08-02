## exercise 11.1 text
Language chosen: **Ruby**

## CI setup
- Linting
    - For linting, I chose RuboCop. It seems to be the most popular linter for Ruby, and I had a quick look at the documentation. It seemed to be fairly easy to set up and use. It is also open source, which is a nice extra.
- Testing
    - For testing, I found RSpec and Minitest. Both seem to be widely used by Ruby developers.
- Building
    - Ruby seems to be an interpreted language, so it doesn't need to be built.

## Alternative options
Some other alternatives include:
- CircleCI: a popular cloud-based CI/CD platform used by many developers and teams.
- Pantheon: a cloud-based CI/CD platform specialized for web-development.
- Ozone: a cloud-based platform offering no-code CI/CD experience.

## self-hosted or cloud-based?
Why choose cloud-based?
- Cloud-based solutions are probably easier to maintain and set up since you don't have to manage the underlying infrastructure.

Why choose self-hosted?
- Self-hosting might offer better flexibility, control, and tools compared to the cloud-based approach since you are not restricted to cloud providers' tools or software.
- Self-hosting might improve cybersecurity since you are running your code locally on your own hardware.
- You have the ability to choose and upgrade your hardware based on the performance you need.

Server uptime:
- With self-hosted CI/CD, you are not affected by outages on your cloud provider's end. However, with self-hosted setups, you might encounter problems or errors with your own setup or hardware, and you will need to handle these issues yourself.

Costs:
- In the short term, cloud providers are probably cheaper since you don't need to set up or buy your own hardware. They may also offer some free credits or server space initially.
- In the long term, self-hosting might become cheaper. Once the hardware is acquired, the only running cost is maintenance, which in the long run might be much cheaper than renting cloud providers' servers.