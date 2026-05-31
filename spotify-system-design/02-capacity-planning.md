Song Storage:
- 3MB * 30M songs = 90 TB of raw audio data.
- This doesn't include replicas.
- No versioning
- Otherwise the size is more 2-3x more.

User Metadata:
- User profiles, perferences and playlists data are ~1KB * 500k users = 0.5GB

Song Metadata:
- Each songs needs a title, artist references, duration, files URLs and so on.
- At roughly 100 bytes per song * 30M songs = 3 GB

Daily Bandwidth:
- The average listen time is 3.5 minutes as 128 - 160kbps; that's roughly 3-4MB per stream.
- Let's assume each user streams 10-15 songs daily.
- This leads to significant egress costs.