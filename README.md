# Ubuntu Snap - nginx
Package nginx in an Ubuntu Snap

## Steps to get nginx snap

1. Git clone the repository
```
git clone https://github.com/kbavishi/nginx-snapcraft.git
```
2. Build the nginx snap
```
cd nginx-snapcraft
snapcraft
```
3. Install the built nginx snap
```
sudo snap install --devmode nginx_0.1_amd64.snap
```
4. Run your nginx snap
```
sudo snap run nginx.nginx
```

## Inspiration

1. [lihow731's nginx snap](https://github.com/lihow731/nginx-snap) for Snapcraft v0.3, which doesn't compile anymore.
