# ClickUp Web app for linux

This is a simple web app for linux that allows you to use ClickUp in a window.

## Requeriments

-   node
-   npm
-   dpkg or dnf

## To build:

1. Clone the repository

```bash
git clone https://github.com/spectrasonic117/clickup-app.git
```

2. Download the dependencies

```bash
cd clickup-app
npm i
```

3. Build the project

```bash
npm run make
```

4. Install the app

```bash
#for Debian / Ubuntu
cd out/make/deb/x64
sudo dpkg -i clickup_1.0.0_amd64.deb



#for Fedora / RedHat
cd out/make/rpm/x64
sudo rpm -i clickup-1.0.0-1.x86_64.rpm
```
