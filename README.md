

# React-Phone-Input-2-Otmane-EH
Highly customizable phone input component with auto formatting, now featuring enhanced phone number formatting options.

[![npm version](https://img.shields.io/npm/v/react-phone-input-2-otmane-eh.svg?style=flat)](https://www.npmjs.com/package/react-phone-input-2-otmane-eh)
[![npm downloads](https://img.shields.io/npm/dm/react-phone-input-2-otmane-eh.svg?style=flat)](https://www.npmjs.com/package/react-phone-input-2-otmane-eh)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](https://github.com/[your-github-username]/react-phone-input-2-otmane-eh#contributing)

## Custom Features in This Fork
- **Custom Phone Number Formatting**: Enhanced support for different phone number formats, including the option to include country code specifics like `+33 (0)` for France.

## Installation
```shell-script
npm install react-phone-input-2-otmane-eh --save
```

## Usage
Import and use the component with your desired configuration. This fork adds additional props for custom formatting.

```jsx
import PhoneInput from 'react-phone-input-2-otmane-eh'
import 'react-phone-input-2-otmane-eh/lib/style.css'

<PhoneInput
  country={'us'}
  value={this.state.phone}
  onChange={phone => this.setState({ phone })}
  customFormattingOption={true} // New prop for enabling custom formatting
/>
```

## Custom Formatting
To utilize the custom formatting feature, ensure you enable the `customFormattingOption` prop and configure the formatting options according to your needs.

```jsx
<PhoneInput
  customFormattingOption={true}
  // Other props as needed
/>
```

### New Prop: `customFormattingOption`
- **Type**: `boolean`
- **Description**: Enables custom formatting for phone numbers. When set to `true`, phone numbers will be formatted according to the new rules defined in this fork.

## Contributing
Contributions to this fork are welcome! Whether it's bug fixes, feature additions, or improvements to the documentation, your help is appreciated. Please refer to the original repository for guidelines and extend them as necessary for the new features introduced by this fork.

## Support
If you find this fork useful and would like to support its development, consider contributing via GitHub or reaching out to discuss more substantial support.

