//--------- VetTube ---------//
Developers: Christopher Molitoris & Mathew Taylor

Created after and inspired by YouTube. Utilizes Django/Python backend REST API and SQL database. Maintains capabilities such as searching for a video or channel and allowing the user to parse the results as well as other recommended videos related to the one selected. The user can then create/add a comment to the video and reply to other comments which are stored within the database. Along with the video presented an algorithm is used to reformat text found within the JSON request (description) to display it as it were to be on YouTube, itself. Calls to the YouTube V3 API and our Django API are made with Axios.

The front-end utilizes Javascript, JSX, HTML, and CSS using React and Bootstrap/React-Bootstrap libraries to create an appealing and easy to use UI/UX for the user. The application was designed with a mobile-first mentality to allow the same functionality and clarity regardless if on desktop or mobile device. The overall design takes into account easy readability, purposeful color choices to draw the user's eyes, and a clear and simple navigation of each functionality. The design also leaves open space for user account menus and functionality along with other quality of life features that can be added depending on client necessity as needed.