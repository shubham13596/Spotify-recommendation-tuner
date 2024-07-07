# Spotify Recommendation Tuner

## Introduction

What if, instead of tapping at different songs and being at the mercy of playlist recommendations, Spotify allowed users to alter their recommendations from the UI itself?

This project is a proof of concept that demonstrates how users could potentially edit their song recommendations based on certain parameters.

## The Concept

At times, a user might feel like listening to songs that are:
- More energetic or fast-paced than Spotify's current recommendations
- More instrumental than usual

This demo allows users to adjust two key parameters:
1. Energy
2. Instrumentalness

## How It Works

1. The app sets initial values for 'energy' and 'instrumentalness' based on the user's existing listening history.
2. It then seeds existing recommendations with the new values chosen by the user to suggest new songs.

Formula:
Existing recommendations + User-chosen values of Energy & Instrumentalness = New recommendations

![](https://github.com/shubham13596/Spotify-recommendation-tuner/blob/main/streamlit-app-2024-06-30-17-06-43-ezgif.com-video-to-gif-converter.gif)


## Why This Matters

1. **User Control**: Highly discerning users (often premium subscribers) would appreciate having some control over what they listen to in a particular session.
2. **Reduced Churn**: Giving users more control could potentially reduce churn rates.
3. **Transparency**: As people become more aware of how algorithms determine their habits, there might be a shift towards allowing users to fine-tune their recommendations.

## Future Possibilities

With the advancement of Large Language Models (LLMs), users might even be able to fine-tune their recommendations using natural language in the future.

## Feedback

We're happy to hear your views and comments on this concept. Feel free to open an issue or submit a pull request!

## Disclaimer

This is a proof of concept and is not affiliated with or endorsed by Spotify.
