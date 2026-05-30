# Survey Form

A clean, responsive customer feedback survey form that collects valuable feedback from users about services provided.

[Live Demo](https://reyrove.github.io/survey-form/)

## Features

- User-friendly form layout
- Required fields with validation (name, email)
- Age input with number range validation (10-100 years)
- Dropdown selection for service type
- Radio buttons for service rating
- Checkboxes for multiple selection preferences
- Textarea for additional comments
- Responsive design for all devices
- Clean and modern interface

This project was built as part of my learning journey with freeCodeCamp

## How It Works

1. User fills out the form with their information
2. Name and email fields are required
3. Age must be between 10 and 100
4. User rates the service and selects preferences
5. Additional comments can be added
6. Submit button sends the form data

## Form Fields

| Field | Type | Required | Validation |
|-------|------|----------|------------|
| Name | Text | Yes | Must not be empty |
| Email | Email | Yes | Must be valid email format |
| Age | Number | No | Between 10 and 100 |
| Service Type | Dropdown | No | Delivery or Pickup |
| Service Rating | Radio | No | Excellent or Good |
| Preferences | Checkbox | No | Speed, Quality, Support |
| Comments | Textarea | No | Free text feedback |

## Technologies Used

- HTML5
- CSS3

## Installation

1. Create a new folder on your computer
2. Save the following files in that folder:
   - `index.html` (the HTML structure)
   - `styles.css` (the styling)
3. Open `index.html` in any modern web browser

## File Structure

```
survey-form/
├── index.html
├── styles.css
├── README.md
├── LICENSE
└── .gitignore
```

## Usage Examples

**Sample Form Submission:**
- Name: John Doe
- Email: john@example.com
- Age: 28
- Service: Delivery
- Rating: Excellent
- Liked: Speed, Quality
- Comments: Great service!

## Browser Support

Works on all modern browsers including:
- Google Chrome
- Mozilla Firefox
- Safari
- Microsoft Edge

## Customization

You can modify:
- Form fields and validation rules
- CSS styles for different themes
- Question types and options
- Form layout and structure

## License

MIT License - see the LICENSE file for details

## Acknowledgements

This project was built as part of my learning journey with freeCodeCamp. The requirements and concept are based on their Responsive Web Design certification.