Nexus
=====

Display relevant information that the user can process in a glance with minimal interaction. 
The project is designed to be used in conjunction with a Raspberry Pi, and should, ideally, 
not require a mouse or keyboard to use. An Internet connection will be required to facilitate
fetching data from various sources to display.

## Initial Requirements

- Social media notifications
  - Twitter direct messages, retweets, and mentions.
- Upcoming calendar events
  - via Google calendar, because it syncs with both iOS and Android calendars very well.
- GitHub Integration
  - Show last commit to last repository
  - Open pull requests
- RSS Feed News Ticker
- Timestamp of most recent “sync”
- Weather
- Automatic updating

## Development Details

To get started with development, fork the repository on GitHub. Now, from your fork,

```bash
git clone https://github.com/<username>/Nexus.git
cd Nexus
npm install
bower install
```

You can browse through the Gruntfile to see exactly what all is avaliable. To get everything 
started up so that you can see what's happening, you can run `grunt serve`. 
