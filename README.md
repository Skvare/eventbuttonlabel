# EVENT REGISTRATION BUTTON LABEL

![Screenshot](/images/event_registration_buttons.png)

## Overview

The Event Registration Button Label extension provides CiviCRM administrators with complete control over button text and messaging on event registration and confirmation pages. This extension allows you to customize the user experience by replacing generic button labels with event-specific, branded, or multilingual text that better matches your organization's voice and event context.

**Key Features:**
- Customize registration button labels on event registration pages
- Modify confirmation button text on event confirmation pages
- Control "Skip Participant" button visibility for additional participants
- Hide or customize status messages during registration process
- Event-specific customization (different labels for different events)
- Support for multilingual button labels
- No coding required - simple form-based configuration
- Maintains CiviCRM's existing registration workflow


## Benefits

- **Enhanced User Experience:** Clear, contextual button labels guide users through registration
- **Brand Consistency:** Match button text to your organization's voice and terminology
- **Event-Specific Messaging:** Different labels for workshops, conferences, fundraisers, etc.
- **Multilingual Support:** Customize labels for different languages and audiences
- **Reduced Confusion:** Eliminate generic "Register" buttons with specific action words
- **Professional Appearance:** Polish your event registration pages with custom messaging

## Use Cases

This extension is particularly valuable for:
- **Branded Events:** Corporate events requiring specific terminology
- **Fundraising Events:** Using donation-focused language ("Support", "Contribute")
- **Educational Programs:** Academic-friendly terms ("Enroll", "Join Class")
- **Membership Events:** Member-specific language ("Reserve Spot", "Claim Seat")
- **International Events:** Localized button text for different regions
- **Multi-step Registrations:** Clear navigation with contextual button labels

## Requirements

- **CiviCRM:** 5.28 or higher
- **PHP:** 7.1 or higher (recommended 7.4+)
- **Permissions:** Administrative access to manage events and custom fields
- **CMS:** Compatible with Drupal, WordPress, Joomla, and Backdrop

## Installation (Web UI)

* Move the downloaded extension to your extensions folder.
* Goto civicrm/admin/extensions -- install the extension

## Installation (CLI, Git)

Sysadmins and developers may clone the [Git](https://en.wikipedia.org/wiki/Git) repo for this extension and
install it with the command-line tool [cv](https://github.com/civicrm/cv).

```bash
git clone https://github.com/Skvare/eventbuttonlabel
cv en eventbuttonlabel
```

## Configuration

### Initial Setup

After installation, the extension automatically creates a custom field group with the necessary fields for button label customization.

### Event-Specific Configuration

1. **Navigate to Event Management:**
  - Go to **Events > Manage Events**
  - Select an existing event or create a new one
  - Click **Configure** for your event

2. **Locate Button Label Settings:**
  - Scroll to the **Event Registration Button Labels** section
  - This section contains custom fields for button customization

3. **Available Button Label Fields:**
  - **Registration Button Label:** Text for the main registration button
  - **Confirmation Button Label:** Text for the confirmation page button
  - **Continue Button Label:** Text for multi-step registration continue buttons
  - **Back Button Label:** Text for navigation back buttons (if applicable)

### Button Label Options

#### Registration Page Buttons

**Default Behavior:** If no custom label is specified, CiviCRM uses default text ("Register")

**Custom Examples:**
- **Workshop:** "Reserve My Spot"
- **Conference:** "Secure Registration"
- **Fundraiser:** "Join the Cause"
- **Training:** "Enroll Today"
- **Membership Event:** "Claim Your Place"

#### Confirmation Page Buttons

**Default Behavior:** Generic confirmation button text

**Custom Examples:**
- **Payment Required:** "Complete Payment"
- **Free Events:** "Confirm Registration"
- **Waitlist Events:** "Join Waitlist"
- **Member Events:** "Finalize Registration"

### Advanced Settings

#### Skip Participant Button Control

**Purpose:** Control visibility of "Skip Participant" button on additional participant screens

**Configuration:**
1. Locate **Hide Skip Participant Button** checkbox
2. Check to hide the button for cleaner user flow
3. Uncheck to maintain default CiviCRM behavior

**Use Cases:**
- **Mandatory Information:** When all participant details are required
- **Simplified Registration:** Reduce user confusion in complex forms
- **Data Quality:** Ensure complete participant information collection

#### Status Message Management

**Purpose:** Control display of status messages during registration process

**Configuration:**
1. Find **Hide Status Messages** option
2. Enable to create cleaner registration experience
3. Disable to maintain informational messages

**Benefits:**
- **Streamlined UI:** Reduce visual clutter during registration
- **Custom Messaging:** Replace with your own status indicators
- **Mobile Optimization:** Better experience on smaller screens

## Support and Contributing

- **Issues:** Report bugs and feature requests on [GitHub Issues](https://github.com/Skvare/eventbuttonlabel/issues)
- **Documentation:** Additional guides available in the project wiki
- **Contributing:** Pull requests welcome! Please follow CiviCRM coding standards
- **Community Support:** Join discussions on [CiviCRM Chat](https://chat.civicrm.org)

## About Skvare

Skvare LLC specializes in CiviCRM development, Drupal integration, and providing technology solutions for nonprofit organizations, professional societies, membership-driven associations, and small businesses. We are committed to developing open source software that empowers our clients and the wider CiviCRM community.

**Contact Information**:
- Website: [https://skvare.com](https://skvare.com)
- Email: info@skvare.com
- GitHub: [https://github.com/Skvare](https://github.com/Skvare)

## Support

[Contact us](https://skvare.com/contact) for support or to learn more.

---

## Related Extensions

You might also be interested in other Skvare CiviCRM extensions:

- **Database Custom Field Check**: Prevents adding custom fields when table limits are reached
- **Image Resize**: Resize images uploaded to CiviCRM with different dimensions
- **Unlink User Account**: Safely unlink user accounts from contacts without deleting data
- **Online Page Setting**: Customize messages for event, contribution, and membership pages when they are not available

For a complete list of our open source contributions, visit our [GitHub organization page](https://github.com/Skvare).

## Credits

Developed by [Skvare, LLC](https://skvare.com) for the CiviCRM community.

## License

This extension is licensed under [AGPL-3.0](LICENSE.txt).
