# Kids-Explicit-Website-Blocker-Extension.

**Kids Safety Blocker** is a Chrome extension designed to help parents safeguard their children from adult-themed websites. By redirecting users to a random educational website such as Khan Academy, Code.org, or freeCodeCamp, this extension ensures that young internet users remain engaged with valuable and educational content.

## Features

- **Automatic Redirection:** Automatically redirects users from blocked sites to educational websites.
- **Customizable Blocking List:** Easily add or remove sites to/from the block list in the `blocker.js` file.
- **User-Friendly:** Simple setup and easy to use for parents looking to ensure a safer browsing experience for their children.

## How to Use

1. **Enable Developer Mode:**
   - Open Chrome and go to the [Extensions](chrome://extensions/) page.
   - Toggle the "Developer mode" switch in the top right corner.

2. **Clone the Repository:**
   - Clone this project to your local machine using Git:
     ```bash
     git clone https://github.com/Soumyojyotisaha/Kids-Explicit-Website-Blocker-Extension..git
     ```

3. **Load the Extension:**
   - On the Extensions page, click "Load unpacked."
   - Select the project folder you cloned.

4. **Add Sites to Block:**
   - Open `blocker.js` in your project folder.
   - Add the host names of any new sites you want to block to the `host` array.

## Example Usage

When a user attempts to visit a blocked website, the extension will automatically redirect them to a random educational website. This ensures a safe browsing experience and promotes learning.

## Screenshots

![Kids Safety Blocker](https://github.com/Soumyojyotisaha/Kids-Explicit-Website-Blocker-Extension./blob/main/snapshot.jpg)

## Contribution

Feel free to contribute to the project by submitting issues, pull requests, or feature requests. Your feedback and improvements are highly appreciated!

## License

This project is licensed under the [MIT License](LICENSE). See the LICENSE file for details.

