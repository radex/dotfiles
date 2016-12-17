## Moving checklist

1. Sign up to iCloud, Dropbox, other internet accounts
2. Set up Keychain, certificates, password manager
3. Apps
	- Copy `/Applications`
	- App preferenecs
4. System preferences
	- Text shortcuts
	- Custom keyboard layout -- here
	- Karabiner
	- Dock
	- Screenshots
5. Dotfiles
	- Shell (prezto/oh-my-zsh, zshrc)
	- .ssh
	- git config
	- .marks
6. Developer environment, package managers
	- iTerm + settings
	- Homebrew + packages
	- Cask packages
	- ruby environment: rbenv, newest version, gems
	- node environment
5. Utilities
	- Quick Look plugins
	- TextMate bundles -- here
		* `/Users/radex/Library/Application\ Support/TextMate/Bundles`
	- Services (`~/Library/Services/`) -- here
	- Launch Agents `~/Library/LaunchAgents` -- here
		* `io.radex.sshadd.plist` -- Workaround for Sierra not loading ssh keys from Keychain.
	- Fonts (`~/Library/Fonts`)
6. Users/ data
	- Mail library (`~/Library/Mail`)
	- Photos library
	- iTunes library
	- iMessage library/history (`~/Library/Messages`)
	- Desktop
	- Documents
	- Downloads
	- Wallpapers
7. Backups, security
	- Double check FileVault is on
	- Turn on firmware password
	- Turn on security notice
	- Set up new Time Machine
	- Set up online backup (Backblaze/Arq)
	- Update passwords
	- Firewall settings