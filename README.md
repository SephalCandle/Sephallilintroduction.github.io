<!DOCTYPE html>
<html>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <head>
        <title>More Detailed Information of Sephal</title>
    </head>
    <body style="background-color: black">
        <h1 style="color:aliceblue">Detailed Information</h1>
        <hr>
        <h2 style="color:aliceblue">Self Infos:</h2>
        <ul style="color:aliceblue">
            <li>Name: Sephal / Ashley Tran</li>
            <li>Ages: 14</li>
            <li>Birthday: November 15<sup>nd</sup></li>
            <li>Favorites: Roblox, Programming</li>
            <li>Gender: Male</li>
        </ul>
        <h1 style="color:antiquewhite;text-align: center;font-family: Arial, Helvetica, sans-serif;">My Schedule</h1>
        <table bgcolor="black">
            <tr bgcolor="orange" align="center">
                <th>Day/Time (GMT +7)</th>
                <th>Monday</th>
                <th>Tuesday</th>
                <th>Wednesday</th>
                <th>Thursday</th>
                <th>Friday</th>
                <th>Saturday</th>
                <th>Sunday</th>
            </tr>
            <tr bgcolor="lightgray" align="center">
                <td>Able to chat</td>
                <td>5:35 PM - 10:00 PM</td>
                <td>5:35 PM - 10:00 PM</td>
                <td>5:35 PM - 10:00 PM</td>
                <td>5:35 PM - 10:00 PM</td>
                <td>5:35 PM - 10:00 PM</td>
                <td>8:00 AM - 11:00 PM</td>
                <td>8:00 AM - 11:00 PM</td>
            </tr>
        </table>
        <h2 style="color: whitesmoke"></h2>
        <br>
        <audio loop controls id="background-music">
            <source src="https://vgmsite.com/soundtracks/tower-defense-simulator-roblox-music-gamerip-windows-gamerip-2019/lsauinggnf/7.%20New%20Hardcore%20Lobby.mp3" type="audio/mp3">
            Your browser isnt support the audio element
        </audio>
        <div>
        <button onclick="var1()" style=" orange; color: blanchedalmond;align-items: center;border-radius: 5px;border-color: aquamarine;">Credits one who help me study HTML5</button>
        </div>
        <h1 style="color: aliceblue;font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;" id="type">Click the above?</h1>
        <script>
            function var1(){
                document.getElementById("type").innerHTML = "Yes, you clicked it" 
            }      
        </script>
        <form action="action_page.txt" method="post" style="background-color: rgb(50, 54, 53);text-align: center;">
            <div>
                <h1 style="color: bisque;font-style: italic;">Online Informations</h1>
                <label for="niname" style="color: aliceblue;font-family: Arial, Helvetica, sans-serif;">Nickname:</label>
                <input type="text" id="niname" name="niname" placeholder="Type your Discord name" required>]
            </div>
            <div>
                <label for="Knowfrom" style="color:aliceblue;font-family: Arial, Helvetica, sans-serif;">Know Sephal From?</label>
                <select required>
                    <option value="ScratchCoders"> Scratch Coders Discord Server</option>
                    <option value="strangers">Random adding</option>
                    <option value="BlueberryPancake">Blueberry Pancake Club Server</option>
                    <option value="ScratchPlatform">Scratch Platform</option>
                </select>
            </div>
            <div>
                <h1 style="color:bisque;font-family: Arial, Helvetica, sans-serif;">Real Informations (Optional)</h1>
                <label for="fname" style="color:aliceblue;font-family: Arial, Helvetica, sans-serif">First Name: </label>
                <input type="text" id="fname" name="fname" placeholder="Type your real first name">
            </div>
            <div>
                <label for="sname" style="color:aliceblue;font-family: Arial, Helvetica, sans-serif">Last Name: </label>
                <input type="text" id="lname" name="lname" placeholder="Type your real last name">
            </div>
            <div>
                <label for="gender" style="color:aliceblue;font-family: Arial, Helvetica, sans-serif">Gender: </label>
                <select>
                    <option value="male">Male</option>
                    <option value="female">Female</option>
                    <option value="non-binary">Non-binary</option>
                    <option value="none">Not prefer to say</option>
                </select>
            </div>
            <div>
                <label for="email" style="color:aliceblue;font-family: Arial, Helvetica, sans-serif">Your email</label>
                <input type="email" id="email" name="email" placeholder="Ex:Ashley1560@gmail.com">
            </div>
            <div>
                <label for="comment" style="color:aliceblue;font-family: Arial, Helvetica, sans-serif">Comment</label>
                <textarea id="comment" name="comment" placeholder="Say your thought about me :3" rows="5" cols="30"></textarea>
            </div>
            <div>
                <input type="reset"><br>
            </div>
            <div>
                <input type="submit">
            </div>
        </form>
    </body>
</html>
