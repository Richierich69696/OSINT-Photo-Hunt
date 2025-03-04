# OSINT-Photo-Hunt
Hey, I’m Raj—Master’s in Info Systems and Security, OSINT junkie. This project’s a no-code adventure: hunting clues in photos online without touching a script. It’s all about finding secrets in pics—like where they’re from—using free tools and my detective hat!

What’s the Big Idea?

Photos spill secrets—dates, places, even who took ‘em. I grab public pics from social media or forums and dig into their metadata or background details. No coding, just sleuthing.

How I Made It Happen

Here’s my chill process, like I’m flipping through pics with you:

1. Pick a Target: Found a public photo—like a random Instagram post tagged #travel.
   Example: A beach pic captioned “Chillin’.”

2. Check Metadata: Used ExifTool to peek at the photo’s hidden info—like when and where it was snapped.
   Example: Saw “2023-05-15, GPS: Miami Beach.”

3. Spot Clues: Zoomed in with my eyes—landmarks, signs, anything in the background.
   Example: A “Miami Surf Shop” sign in the corner.

4. Map It: Plugged clues into Google Maps—found the exact spot!
   Example: “Miami Beach, near 5th St”—boom, located!

Stuff You’ll Need

ExifTool: Free from exiftool.org—reads photo metadata.

Web Browser: Brave or Mullavad, duckduck go,Chrome or whatever—grabs pics.
Google Maps: Free online—maps your finds.
Notepad: To jot clues—no extra download.

Let’s Do It—Step by Step with Commands

1. Get Tools:
   - ExifTool: exiftool.org, download the .exe (Windows) or .tar.gz (Mac),
   - unzip to this folder. Rename it “exiftool.exe” for ease.
   - Browser/Maps: You’ve got ‘em already!

2. Set Up Folder: You’re in RajCyberAIProjects/OSINTPhotoHunt—perfect!
   Command: In command line, “cd RajCyberAIProjects\OSINTPhotoHunt” (Windows)
    or
   “cd RajCyberAIProjects/OSINTPhotoHunt” (Mac) if you’re navigating.

4. Grab a Pic: Open your browser, find a public photo (e.g., Instagram #nature),
5.  right-click, “Save as” “test.jpg” in this folder.

6. Check Metadata: Command line, type “exiftool test.jpg” (Windows)
7. or
8. “./exiftool test.jpg” (Mac)—hit enter. Look for “Date” or “GPS.”
   Save it: “exiftool test.jpg > metadata.txt” to keep it here.

9. Eyeball It: Open “test.jpg” in your photo viewer, zoom in—note anything (signs, landmarks) in Notepad as “clues.txt.”
   Example: “Sign says ‘Miami Surf’.”

10. Map It: Open maps.google.com, type your clues (e.g., “Miami Surf Shop”),
11. see where it lands.
12.  Write it in “clues.txt.”

Bumps in the Road

No Metadata: New pics might be scrubbed—try old ones.
Blurry Clues: Can’t read signs? Guess from context.
Legal Vibes: Stick to public pics—don’t creep!

Why I Love It

It’s detective work with zero code—pure OSINT fun. Shows my sleuthing skills!
