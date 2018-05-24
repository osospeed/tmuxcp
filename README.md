# tmuxcp
Transfer files between panes without network.

Target pane is currently hardcoded `0`. You can view pane numbers by `prefix` + <kbd>q</kbd>.

Then from your source pane :
- Linux target:
`tmuxcpl /etc/passwd`
- Window target:
`tmuxcpw /etc/passwd`

# TODO
- [ ] Source is currently linux only
- [ ] Add option to retrieve files from target
- [ ] Contribute ...
