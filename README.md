# Mika 4 Muck

 Mika: The best actively-developed Muck hacked client
## Installing
<details markdown="1">
 <summary>I am using Windows</summary>
 1. Download the `MIKAssembly-CSharp.dll` file from the github.<br>
 2. Rename the file to `Assembly-CSharp.dll`<br>
 <img src="https://user-images.githubusercontent.com/57292172/226772490-125e7ac9-b45b-4916-a19a-105301d19b1d.png"><br>
 3. Open up your Steam library and go to Muck.<br>
 <details><summary>Step 3 Image</summary><img src="https://user-images.githubusercontent.com/57292172/226771622-41db3baa-f81a-43ca-a29a-1f7d3b811971.png"></details>
 4. Browse the local files of Muck<br>
 <details><summary>Step 4 Image</summary><img src="https://user-images.githubusercontent.com/57292172/226771822-449e3554-690d-448d-89d9-52bd64e146a0.png"></details>
 5. Open the Muck_Data folder<br>
 <img src="https://user-images.githubusercontent.com/57292172/226772262-390ae52c-955f-4d32-a331-7dddc21228d3.png"> <br>
 6. Open the Managed foler <br>
 <img src="https://user-images.githubusercontent.com/57292172/226772320-eb2e25b6-1abb-45bf-b2df-5365e50348b7.png"> <br>
 7. Drop the file from your Downloads into the Managed folder<br>
 <img src="https://user-images.githubusercontent.com/57292172/226772888-2bd150d6-59c6-4a26-9126-9868a699c4f9.png"> <br>
 8. Open Steam and launch Muck!<br>
</details>
<details markdown="1">
 <summary>I am on Mac</summary>
 1. Download the `MIKAssembly-CSharp.dll` file from the github.<br>
 2. Rename the file to `Assembly-CSharp.dll`<br>
 <img src="https://user-images.githubusercontent.com/57292172/226772490-125e7ac9-b45b-4916-a19a-105301d19b1d.png"> <br>
 3. Open up your Steam library and go to Muck.<br>
 <details><summary>Step 3 Image</summary><img src="https://user-images.githubusercontent.com/57292172/226771622-41db3baa-f81a-43ca-a29a-1f7d3b811971.png"></details>
 4. Browse the local files of Muck<br>
 <details><summary>Step 4 Image</summary><img src="https://user-images.githubusercontent.com/57292172/226771822-449e3554-690d-448d-89d9-52bd64e146a0.png"></details>
 5. Right-Click on the Muck app and click "Show Package Contents"<br>
 6. Go to MacOS folder and then find a folder with a lot of `.dll` files in it. (usually named Managed or Data)<br>
 5. Drop the file from your Downloads into this folder.<br>
</details>
<details markdown="1">
 <summary>I am using Linux</summary>
  Go to steam -> muck -> settings icon -> browse local files -> find the folder with assembly-csharp.dll -> paste the Mika one but replace the filename with `Assembly-CSharp.dll`.
</details>

## Commands
**First of all, get into the game and click Enter to open the chatbox**
* Key: &lt;option&gt; means required. [option] means optional.
* `/heal` - Heals you for 500 health, shield, and stamina.
* `/fastak` - Adds 150 attack speed
* `/slotak` - Removes 150 attack speed
* `/power` - Spawns every powerup at your location, and if you dont move, redeems them two seconds later.
* `/magnet` - Picks up all nearby floor-items (ex. rocks, shrooms, apples)
* `/chest` - Opens all powerup chests. Does not redeem them.
* `/achieve` - Gives you all achievements on Steam.
* `/muck` - Gives you the **Muck** achievement on Steam.
* `/dupe` - Drops your current item.
* `/boat` - Drops all items needed to fix the boat.
* `/drop` - Drops a stack of &lt;item&gt; [amount] times. Examples: `/drop rock`, `/drop rock 1`, `/drop adamantite_sword`

## How do I hack muck myself?
Install dnSpy or JetBrains dotPeek, then open up the Assembly-CSharp.dll in the app. Modify the code, export it, and boom!
I recommend watching [this video](https://www.youtube.com/watch?v=_j7Plxkvn9Y) to get started.
> Not avalible on mac.
