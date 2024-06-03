## Work Day Scheduler HTML Structure

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
- **Title**: "Work Day Scheduler"

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