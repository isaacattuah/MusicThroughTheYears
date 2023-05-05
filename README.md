# Music Through The Years

This is a Flask app that allows you to search for the top 10 tracks from any given year using the Spotify API.

## Getting Started

To get started, you'll need to set up your own Spotify developer account and obtain a `CLIENT_ID` and `CLIENT_SECRET`. Here's how:

1. Go to the [Spotify Developer Dashboard](https://developer.spotify.com/dashboard/) and log in with your Spotify account.

2. Create a new app by clicking the "Create a Client ID" button. Follow the prompts to fill out the necessary information.

3. Once your app is created, you should be taken to a page that displays your `CLIENT_ID` and `CLIENT_SECRET`. Keep this information safe, as you'll need it later.

4. In the Replit editor, navigate to the `.env` file and add your `CLIENT_ID` and `CLIENT_SECRET` like this:

   ```python
   CLIENT_ID=your_client_id_here
   CLIENT_SECRET=your_client_secret_here
   ```

   Make sure to replace `your_client_id_here` and `your_client_secret_here` with your actual `CLIENT_ID` and `CLIENT_SECRET`.

5. Save the `.env` file.

## Running the App

To run the app, simply run the `main.py` file.

```bash
python main.py
```

This will start the Flask app on port `81`.

Once the app is running, open your web browser and go to `http://localhost:81/`. You should see the app's homepage.

Need an easier way? [Run the app on Repl.it here](https://replit.com/@isaacattuah/MusicThroughTheYears)

## Using the App

To search for tracks from a particular year, enter the year into the input field and click the "Go" button. The app will retrieve the top 10 tracks from that year and display them in a table.

You can listen to a track by clicking the "play" button next to it.

## Contributing

If you'd like to contribute to this project, feel free to submit a pull request.
