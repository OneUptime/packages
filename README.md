# OneUptime packages

The GitHub Pages site behind https://packages.oneuptime.com: the signed apt and
yum repositories of the OneUptime infrastructure agent.

OneUptime's release workflow writes it: the `publish-infrastructure-agent-apt-yum`
job in [OneUptime/oneuptime](https://github.com/OneUptime/oneuptime)
(`.github/workflows/release.yml`, `Scripts/PackageManagers/`) adds each release
and replaces this branch's one commit. Do not edit it by hand.

How to install the agent from it:
[Server / VM Monitor](https://oneuptime.com/docs/monitor/server-monitor).
