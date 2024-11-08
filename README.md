# Aboriginal Seasonal Calendar Widget

[![Netlify Status](https://api.netlify.com/api/v1/badges/e3c25721-c58f-4b33-9825-94c9a98ed2ad/deploy-status)](https://app.netlify.com/sites/seasonal-au/deploys)

## Project Introduction

### Purpose and Overview

This project aims to enhance understanding and appreciation of Aboriginal seasonal calendars, beginning with the Noongar seasonal calendar. It's a digital widget designed to educate users on the distinct seasons recognized by Aboriginal communities, reflecting their deep connection with the natural world. By providing accessible and interactive content, this initiative seeks to bridge cultural gaps and foster a broader appreciation of Indigenous ecological knowledge and practices. I plan to expand the widget to include additional seasonal calendars in the future.

## How the Widget Works

### Overview

The widget is embedded into web pages through an iframe, allowing for easy integration and use across various platforms. It displays information on the different Noongar seasons and automatically updates at the start of each season. Using the openweathermap.org API to pull in the hourly weather data for Perth, Western Australia.

### iframe for embedding the widget

```html
<iframe
  className="noongar-iframe"
  width="320"
  height="120"
  src="https://mytime.netlify.app/"
  frameborder="0"
  
</iframe>
```

 **Remember to adjust the width & height as needed.**


## Ways to Contribute 

### I Welcome Contributions in Various Forms

- **Improvements:** Suggestions for adding new features, refining existing functionality, or enhancing the user interface.
- **Feedback:** Share your thoughts on usability, educational content, and overall experience.
- **Issue Reporting:** Report bugs, errors, or inconsistencies in the widget's performance or content.
 
Please use the GitHub Issues tab for feedback and issue reporting, and consider submitting pull requests for direct contributions.

## Acknowledgement of Country

I acknowledge Traditional Owners of Country throughout Australia and recognise the continuing connection to lands, waters, and communities. I pay my respects to Aboriginal and Torres Strait Islander cultures; and to Elders past and present.
