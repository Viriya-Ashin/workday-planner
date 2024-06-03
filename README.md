## Workday-Planner HTML Structure

### Head Section
- **Meta Tags**:
  - `charset="UTF-8"`: Specifies character encoding.
  - `name="viewport"`: Ensures proper scaling on different devices.
  - `http-equiv="X-UA-Compatible"`: Sets document mode to edge mode in IE.
- **Stylesheets**:
  - **Bootstrap**: `https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/css/bootstrap.min.css`
  - **Font Awesome**: `https://use.fontawesome.com/releases/v5.8.1/css/all.css`
  - **Google Fonts**: `https://fonts.googleapis.com/css?family=Open+Sans&display=swap`
  - **Custom CSS**: `style.css`
- **Title**: "Workday-Planner"

### Body Section
- **Header**: 
  - Class: `jumbotron`
  - Elements: `h1` (Title), `p` (Description), `p#currentDay` (Current Day Placeholder)
- **Main Container**:
  - Class: `container`
  - **Time Blocks**:
    - Class: `row time-block`
    - Columns: 
      - `div.col-sm-1.hour` (Hour Label)
      - `textarea.col-sm-10.description` (Task Description)
      - `button.col-sm-1.saveBtn` (Save Button with Font Awesome icon)

### Scripts
- **jQuery**: `https://code.jquery.com/jquery-3.4.1.min.js`
- **Moment.js**: `https://cdnjs.cloudflare.com/ajax/libs/moment.js/2.24.0/moment.min.js`

## CSS for Workday-Planner

### Universal Styles
- `*`: Base styles for all elements (margin, padding, box-sizing).

### Root Variables
- `:root`: Defines global variables for consistent styling (fonts, colors, sizes).

### Element Styles
- `body`: Applies global font settings.
- `textarea`: Styles for text areas (background, border, color, padding).
- `.jumbotron`: Styles the header (text-align, background, color, border).
- `.description`: Preserves whitespace.
- `.time-block`: Styles time blocks (text-align, border-radius).
- `.row`: Styles row elements (height, border).
- `.hour`: Styles hour labels (background, color, border).
- `.past`: Styles past time blocks (background, color).
- `.present`: Styles present time blocks (background, color).
- `.future`: Styles future time blocks (background, color).
- `.saveBtn`: Styles save buttons (border, background, color, border-radius).
- `.saveBtn i:hover`: Hover effect for save button icons (font-size, transition).