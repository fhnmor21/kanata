Add kanata.service to: `~/.config/systemd/user/`

Then run:

`systemctl --user daemon-reload`
`systemctl --user enable kanata.service`
`systemctl --user start kanata.service`
`systemctl --user status kanata.service`   # check whether the service is running
