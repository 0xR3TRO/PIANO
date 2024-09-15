## Project Description

### Goal:

The "PIANO" project aims to provide users with a simple, yet functional, web-based piano integrated into a browser. Users can play a virtual instrument without needing to install additional software. The project will have a retro aesthetic, evoking the style of old games and web applications while offering modern functionality.

### Features:

- **Play the piano:** Users can play the virtual piano using their laptop’s keyboard.
- **Retro sounds:** Recreate the sounds of classic pianos and synthesizers from the 80s.
- **Full-screen mode:** An option to extend the application to full screen for a better playing experience.
- **Minimalist recording gallery:** Users can save short music pieces and review their session history.

## Requirements Analysis

### Functional Requirements:

- **Virtual keys:** Each key on the laptop's keyboard will correspond to a key on the virtual piano.
- **Recording:** Ability to record short music pieces and play them back.
- **Sound customization:** Users can choose different retro instrument sounds, such as classic piano, organ, or synthesizer.
- **Full-screen mode:** An option to switch to full-screen mode for a more immersive experience.
- **Retro theme:** The graphic style of the application will have a retro feel (pixel art, neon colors, dark background).

### Non-functional Requirements:

- **Smooth performance:** Fast and responsive interaction with the virtual piano.
- **Browser compatibility:** The application should work on all popular browsers (Chrome, Firefox, Safari).
- **Retro aesthetics:** The retro feel will be present in both the visuals and sounds of the app.
- **Simple interface:** Intuitive, minimalist design so users can start playing immediately without complex options.

## Interface Design

### Sketches/Interface Visuals:

- _Home page:_ A rectangular piano displayed centrally, with keys that react when pressed by the user.
- _Options panel:_ A minimalist panel at the top or side of the page, allowing users to choose sounds, enable full-screen mode, and start recording.
- _Recording window:_ A small rectangular panel that lets users save short pieces and play them back.

### Site Map:

- _Home page_
  - Virtual piano
  - Options panel (sounds, full-screen mode, recording)
  - History of saved music pieces (in a minimalist style)

## System Architecture

### Data Structure Description:

The application stores data related to recorded pieces and user settings:

- **Recordings:** Short sound files saved in the browser’s local storage.
- **User settings:** Information on selected sounds and application settings.

### Architecture Diagrams:

The application will follow the MVC model:

- **Model:** Handles the logic for generating sounds and managing recordings.
- **View:** Displays the virtual piano and other interface elements.
- **Controller:** Manages communication between the view and model, processing user interactions (e.g., key presses).

## Implementation

### Technology Description:

- **Frontend:** HTML, CSS, JavaScript (React.js) – a simple and lightweight browser-based application.
- **Backend:** No backend needed – the app will use local browser storage and does not require a server.
- **Database:** Browser’s local storage (LocalStorage) to store recordings.

### Code Structure:

- _Directories/files:_ Separate files for piano logic, recording, UI handling, and styles.
- _Code writing styles:_ Modular approach to UI components (piano, options panel).

## Testing

### Test Plan:

- **Unit testing:** Checking the correct functioning of the keys, keyboard interaction, recording, and playback.
- **Integration testing:** Ensuring that all interface components (piano, options panel) work correctly together.
- **Compatibility testing:** Testing the application on different browsers and devices.
- **Performance testing:** Assessing the smoothness of sound generation in real-time.

### Testing Procedures:

- Developing test cases for each function, including piano operation and recording.
- Regularly checking compatibility across different devices and browsers.

## Deployment and Maintenance

### Deployment Plan:

- **Deployment stages:** Beta testing in browsers, bug fixes, and final release of the app.
- **Deadlines:** Setting dates for beta release, testing, and final launch.

### Maintenance Procedures:

- **Technical support:** Providing a simple contact form on the website for users to report bugs.
- **Updates:** Regular updates focused on performance improvements and bug fixes reported by users.

## Schedule

### Project Plan:

- **Development stages:**
  - Interface design (2 weeks)
  - Piano logic implementation (4 weeks)
  - Testing and optimization (2 weeks)
- **Deadlines:** The project should be completed in 8 weeks.

## Budget

### Estimated Costs:

- **Development:** Cost of the development team’s work (8 weeks of work, depending on hourly rates).
- **Maintenance costs:** Minimal, as the application doesn’t require servers or expensive resources, aside from occasional updates.
