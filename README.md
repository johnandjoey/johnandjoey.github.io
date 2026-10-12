# johnandjoey.github.io

GitHub Pages site for a personal Tesla Fleet API app.

- `.well-known/appspecific/com.tesla.3p.public-key.pem`: the public half of the app's EC P-256 key. Tesla requires it at this path on the app's domain. The private key never leaves the owner's Mac.
- `callback/`: the OAuth return page. It shows the sign-in address so it can be pasted into the local tool, and sends it nowhere.
- `.nojekyll`: stops GitHub Pages skipping the `.well-known` folder.
