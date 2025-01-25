# Firebase Realtime Database Race Condition

This repository demonstrates a race condition in Firebase's Realtime Database when multiple clients concurrently update the same data.  The `counterBug.js` file shows how this can lead to inaccurate counter values. The solution in `counterBugSolution.js` uses transactions to ensure data consistency.