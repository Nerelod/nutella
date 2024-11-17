This patchfile does two things:
    It creates a backdoor to sshd, allowing authentication with the password "nutella"
    It, by default, creates a controlsocket in /tmp/ that can be used to 'hijack' sessions
