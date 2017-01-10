`clustergpustat`
=========

[![license](https://img.shields.io/github/license/wookayin/gpustat.svg?maxAge=86400)](LICENSE)

Just nvidia-smi across the cluster

Usage
-----

1. `$ gpustat`
    it lists all gpu statistics across the cluster
2. `$ gpufree`
    it lists all gpu free across the cluster
3. `sshfree`
    logins to a random node with a free gpu


Quick Installation
------------------

Just download [gpustat][script_gitio], and/or [gpufree][script_gitio], and/or [gpuonefree][script_gitio] and [sshfree][script_gitio] into somewhere in `PATH`, e.g. `~/.local/bin/`
(when you do not have root privilege, for example):

```
sudo wget https://git.io/gpustat -O /usr/local/bin/gpustat && sudo chmod +x /usr/local/bin/gpustat
sudo wget https://git.io/gpufree -O /usr/local/bin/gpufree && sudo chmod +x /usr/local/bin/gpufree
sudo wget https://git.io/gpuonefree -O /usr/local/bin/gpuonefree && sudo chmod +x /usr/local/bin/gpuonefree
sudo wget https://git.io/sshfree -O /usr/local/bin/gpustat && sudo chmod +x /usr/local/bin/sshfree
```

[script_gitio]: https://git.io/gpustat.py
[script_stable]: https://raw.githubusercontent.com/wookayin/gpustat/v0.2.0/gpustat.py


License
-------

[MIT License](LICENSE)
