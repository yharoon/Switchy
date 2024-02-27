What Languages are we going to use?

# I plan to use rust for the cli.

How are we going to get the relevant music data?

# For Spotify we can use the api, for Apple Music we only need to read from the playlist page so we can just scape the information.

How should it work?

# It should be very simple, by using "switchy-cli add -a2s {playlist url}" it should scrape the music from the apple music playlist url, and create a new playlist in your spotify account with as much recognised music as it can (there may be errors if a specific song cannot be found in spotify or something else). To have the account information, we need a config file that you can change, so we will also have a "switchy-cli config -spotify {relevant information(need to look into this)}" to allow users to create a config file that the cli can use to add the playlists.

Any plans for extensions/revisits?

# At some point, i should get round to paying for the apple dev stuff so i can do it vice versa too. For now i will specify in the cli tool that -a2s (Apple to Spotify) is a default so both "switchy-cli add -a2s {playlist url}" and "switchy-cli add {playlist url}" do the same thing.