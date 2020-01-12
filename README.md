# strava-scripts
Misc. scripts for all things Strava

## Give kudos to every event in your feed
1. Navigate to the main feed page of Strava in a web browser:   
`
  https://www.strava.com/dashboard/following/100
`
2. Replace the "100" in the above URL with whatever number of activities you wish to give kudos to
3. Open Developer Tools in your web browser and navigate to the console
4. Paste the script below into the console and press enter:

```javascript
  document.querySelectorAll('button.js-add-kudo').forEach(function(node) {node.click()});
```

5. Every activity in view should be given Kudos.

### Future Enhancements
- Script that automatically fetches your activity feed and gives kudos
