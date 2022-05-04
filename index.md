<meta http-equiv="Content-Type" content="text/html; charset=utf-8">
<link type="text/css" rel="stylesheet" href="resources/sheet.css">
<div class="ritz grid-container" dir="ltr">
    <table class="waffle" cellspacing="0" cellpadding="0">
        <tbody>
        <tr style="height: 49px">
            <td class="s0" dir="ltr">Check-list ID</td>
            <td class="s0" dir="ltr">Screen</td>
            <td class="s0" dir="ltr">Pre-conditions</td>
            <td class="s0" dir="ltr">Description</td>
            <td class="s0" dir="ltr">Additional Verification</td>
            <td class="s0" dir="ltr">Android</td>
        </tr>
        <tr style="height: 49px">
            <td class="s1" dir="ltr">1</td>
            <td class="s1" dir="ltr" rowspan="2">Splash</td>
            <td class="s2" dir="ltr">When the patient clicks on &#39;Get Started&#39; button</td>
            <td class="s2" dir="ltr">It should redirect patient to the onboarding flow.</td>
            <td class="s2" dir="ltr"></td>
            <td class="s2" dir="ltr"><input type="checkbox" id="vehicle1" name="vehicle1" value="Bike"></td>
        </tr>
        <tr style="height: 49px">
            <td class="s1" dir="ltr">2</td>
            <td class="s2" dir="ltr">When the patient clicks on &#39;Sign in here&#39; button</td>
            <td class="s2" dir="ltr">It should redirect patient to the &#39;Welcome&#39; screen where patient can enter
                mobile number and login to the app.
            </td>
            <td class="s2" dir="ltr"></td>
            <td class="s2" dir="ltr"><input type="checkbox" id="vehicle1" name="vehicle1" value="Bike"></td>
        </tr>
        <tr style="height: 49px">
            <td class="s1" dir="ltr">3</td>
            <td class="s1" dir="ltr" rowspan="14">Onboarding</td>
            <td class="s2" dir="ltr" rowspan="2">Onboarding &gt; Contact Info</td>
            <td class="s2" dir="ltr">Patient should be able to go to next screen by entering valid &#39;First Name&#39;,
                &#39;Last Name&#39; &amp; &#39;Email Address&#39;.
            </td>
            <td class="s2" dir="ltr">Data should show up in the dashboard once the user registers.</td>
            <td class="s2" dir="ltr"><input type="checkbox" id="vehicle1" name="vehicle1" value="Bike"></td>
        </tr>
        <tr style="height: 20px">
            <td class="s1" dir="ltr">4</td>
            <td class="s2" dir="ltr">&quot;Terms of use&quot;, &quot;Privacy Policy&quot; and &quot;Telehealth Consent&quot;
                should be clickable and patient should redirect to the respective screen on clicking it.
            </td>
            <td class="s2" dir="ltr"></td>
            <td class="s2" dir="ltr"></td>
        </tr>
        <tr style="height: 49px">
            <td class="s1" dir="ltr">5</td>
            <td class="s2" dir="ltr" rowspan="2">Onboarding &gt; &#39;One more thing&#39;</td>
            <td class="s2" dir="ltr">Patient should be able to select his/her country from the drop-down.</td>
            <td class="s2" dir="ltr"></td>
            <td class="s2" dir="ltr"></td>
        </tr>
        <tr style="height: 49px">
            <td class="s1" dir="ltr">6</td>
            <td class="s2" dir="ltr">It should send OTP to the entered mobile number on clicking &#39;Continue&#39;.
            </td>
            <td class="s2" dir="ltr"></td>
            <td class="s2" dir="ltr"></td>
        </tr>
        <tr style="height: 49px">
            <td class="s1" dir="ltr">7</td>
            <td class="s2" dir="ltr">Onboarding &gt; &#39;Verify your Number&#39;</td>
            <td class="s2" dir="ltr">Patient should be redirected to the next screen on entering valid OTP.</td>
            <td class="s2" dir="ltr">Data should show up in the dashboard once the user registers.</td>
            <td class="s2" dir="ltr"></td>
        </tr>
        <tr style="height: 20px">
            <td class="s1" dir="ltr">8</td>
            <td class="s2" dir="ltr">Onboarding &gt; &#39;Where do you experience joint pain?&#39;</td>
            <td class="s2" dir="ltr">Patient should be able to select one or all options.<br><br>If &#39;Other&#39; is
                selected then it should show text-box to enter the value.
            </td>
            <td class="s2" dir="ltr">Data should show up in the dashboard once the user registers.</td>
            <td class="s2" dir="ltr"></td>
        </tr>
        <tr style="height: 20px">
            <td class="s1" dir="ltr">9</td>
            <td class="s2" dir="ltr">Onboarding &gt; &#39;Have you been diagnosed with an arthritis-related condition&#39;</td>
            <td class="s2" dir="ltr">If the patient selects &#39;Yes&#39;, it should redirect to &#39;Which diagnosis
                have you received?&#39; screen.<br><br>If patient selects &#39;No&#39;, it should redirect to &#39;What
                is your pain level?&#39; screen.
            </td>
            <td class="s2" dir="ltr"></td>
            <td class="s2" dir="ltr"></td>
        </tr>
        <tr style="height: 20px">
            <td class="s1" dir="ltr">10</td>
            <td class="s2" dir="ltr">Onboarding &gt; &#39;Which diagnosis have you received?&#39;</td>
            <td class="s2" dir="ltr">Patient should be able to select one or all options.<br><br>If &#39;Other&#39; is
                selected then it should show text-box to enter the value.
            </td>
            <td class="s2" dir="ltr">Data should show up in the dashboard once the user registers.</td>
            <td class="s2" dir="ltr"></td>
        </tr>
        <tr style="height: 49px">
            <td class="s1" dir="ltr">11</td>
            <td class="s2" dir="ltr">Onboarding &gt; &#39;What is your pain level?&#39;</td>
            <td class="s2" dir="ltr">It should allow patient to select level of pain from range of 0 to 10.</td>
            <td class="s2" dir="ltr">Data should show up in the dashboard once the user registers.</td>
            <td class="s2" dir="ltr"></td>
        </tr>
        <tr style="height: 49px">
            <td class="s1" dir="ltr">12</td>
            <td class="s2" dir="ltr" rowspan="2">Onboarding &gt; &#39;Book your free 15 minutes consultation
                today&#39;
            </td>
            <td class="s2" dir="ltr">If the patient clicks on &#39;I&#39;ll do this later&#39;, it should redirect to
                &#39;Home screen&#39;.
            </td>
            <td class="s2" dir="ltr"></td>
            <td class="s2" dir="ltr"></td>
        </tr>
        <tr style="height: 20px">
            <td class="s1" dir="ltr">13</td>
            <td class="s2" dir="ltr">If the patient clicks on &#39;Continue&#39;, it should redirect to the next screen
                where patient can schedule appointment with the therapist.
            </td>
            <td class="s2" dir="ltr"></td>
            <td class="s2" dir="ltr"></td>
        </tr>
        <tr style="height: 49px">
            <td class="s1" dir="ltr">14</td>
            <td class="s2" dir="ltr" rowspan="3">Onboarding &gt; &#39;Schedule your evaluation&#39;</td>
            <td class="s2" dir="ltr">If the patient clicks on &#39;I&#39;ll do this later&#39;, it should redirect to
                &#39;Home screen&#39;.
            </td>
            <td class="s2" dir="ltr"></td>
            <td class="s2" dir="ltr"></td>
        </tr>
        <tr style="height: 49px">
            <td class="s1" dir="ltr">15</td>
            <td class="s2" dir="ltr">Patient should be able to book the appointment for any of date from current date to
                next 21 days.<br><br>Patient shouldn&#39;t be able to book appointment for &gt; current + 21 days.
            </td>
            <td class="s2" dir="ltr"></td>
            <td class="s2" dir="ltr"></td>
        </tr>
        <tr style="height: 49px">
            <td class="s1" dir="ltr">16</td>
            <td class="s2" dir="ltr">Patient should redirect to the next screen where he/she can select appointment time
                for selected date.
            </td>
            <td class="s2" dir="ltr"></td>
            <td class="s2" dir="ltr"></td>
        </tr>
        <tr style="height: 49px">
            <td class="s1" dir="ltr">17</td>
            <td class="s1" dir="ltr">Sign-in</td>
            <td class="s2" dir="ltr">Existing patient</td>
            <td class="s2" dir="ltr">Follow check-list id #6, #7 &amp; #8.</td>
            <td class="s2" dir="ltr"></td>
            <td class="s2" dir="ltr"></td>
        </tr>
        <tr style="height: 49px">
            <td class="s1" dir="ltr">18</td>
            <td class="s1" dir="ltr" rowspan="6">Chat</td>
            <td class="s2" dir="ltr">N/A</td>
            <td class="s2" dir="ltr">There should be &#39;Schedule free call&#39; button if there is no appointment
                booked for logged-in patient.
            </td>
            <td class="s2" dir="ltr"></td>
            <td class="s2" dir="ltr"></td>
        </tr>
        <tr style="height: 49px">
            <td class="s1" dir="ltr">19</td>
            <td class="s2" dir="ltr">Schedule free call</td>
            <td class="s2" dir="ltr">Follow check-list id #19, #20 &amp; #21.</td>
            <td class="s2" dir="ltr"></td>
            <td class="s2" dir="ltr"></td>
        </tr>
        <tr style="height: 49px">
            <td class="s1" dir="ltr">20</td>
            <td class="s2" dir="ltr">If appointment is booked</td>
            <td class="s2" dir="ltr">Scheduled date and time should display in the place of &#39;Scheduled free call&#39;
                button.
            </td>
            <td class="s2" dir="ltr"></td>
            <td class="s2" dir="ltr"></td>
        </tr>
        <tr style="height: 49px">
            <td class="s1" dir="ltr">21</td>
            <td class="s2" dir="ltr">Once &#39;Starter game&#39; is completed for fresh patient</td>
            <td class="s2" dir="ltr">Patient should receive a message from therapist.</td>
            <td class="s2" dir="ltr"></td>
            <td class="s2" dir="ltr"></td>
        </tr>
        <tr style="height: 49px">
            <td class="s1" dir="ltr">22</td>
            <td class="s2" dir="ltr">Chat icon badge</td>
            <td class="s2" dir="ltr">If the patient gets any new message from therapist, then the chat icon should
                indicate with a red badge.
            </td>
            <td class="s2" dir="ltr"></td>
            <td class="s2" dir="ltr"></td>
        </tr>
        <tr style="height: 49px">
            <td class="s1" dir="ltr">23</td>
            <td class="s2" dir="ltr">Messages</td>
            <td class="s2" dir="ltr">Patient should be able to send text &amp; images in the chat with therapist.</td>
            <td class="s2" dir="ltr"></td>
            <td class="s2" dir="ltr"></td>
        </tr>
        <tr style="height: 20px">
            <td class="s1" dir="ltr">24</td>
            <td class="s1" dir="ltr" rowspan="4">Home screen</td>
            <td class="s2" dir="ltr">Formation of Home screen for fresh patient</td>
            <td class="s2" dir="ltr">1. Starter game<br>2. Appointment tile (if patient is scheduled for that date)<br>3.
                Bubble shooter<br>4. Block puzzle<br>5. Candy match<br>6. Reactiv assessment (if enabled from therapist
                portal)<br>7. QuickDash questionnaire (if patient is completed, then it should move to 9th
                positions)<br>8. Virtual goniometer<br>9. QuickDash questionnaire (if completed)
            </td>
            <td class="s2" dir="ltr"></td>
            <td class="s2" dir="ltr"></td>
        </tr>
        <tr style="height: 20px">
            <td class="s1" dir="ltr">25</td>
            <td class="s2" dir="ltr">Formation of Home screen for old patient</td>
            <td class="s2" dir="ltr">1. Appointment tile (if patient is scheduled for that date)<br>2. Bubble
                shooter<br>3. Block puzzle<br>4. Candy match<br>5. Reactiv assessment (if enabled from therapist portal)<br>6.
                QuickDash questionnaire (if patient is completed, then it should move to 9th positions)<br>7. Virtual
                goniometer<br>8. QuickDash questionnaire (if completed)
            </td>
            <td class="s2" dir="ltr"></td>
            <td class="s2" dir="ltr"></td>
        </tr>
        <tr style="height: 49px">
            <td class="s1" dir="ltr">26</td>
            <td class="s2" dir="ltr" rowspan="2">Fresh patient</td>
            <td class="s2" dir="ltr">All the tiles should be disabled except &#39;Starter Game&#39; &amp; Appointment
                tile (if patient is scheduled for that date).
            </td>
            <td class="s2" dir="ltr"></td>
            <td class="s2" dir="ltr"></td>
        </tr>
        <tr style="height: 20px">
            <td class="s1" dir="ltr">27</td>
            <td class="s2" dir="ltr">All the tiles should be enabled once the patient completes &#39;Starter game&#39;
                and tile of &#39;Starter game&#39; should be removed on the next day of completing starter game.
            </td>
            <td class="s2" dir="ltr"></td>
            <td class="s2" dir="ltr"></td>
        </tr>
        <tr style="height: 49px">
            <td class="s1" dir="ltr">28</td>
            <td class="s1" dir="ltr" rowspan="3">Telehealth Calls</td>
            <td class="s2" dir="ltr">Appointment tile</td>
            <td class="s2" dir="ltr">Appointment tile should up on the Home screen when a user has an appointment on
                that date
            </td>
            <td class="s2" dir="ltr"></td>
            <td class="s2" dir="ltr"></td>
        </tr>
        <tr style="height: 49px">
            <td class="s1" dir="ltr">29</td>
            <td class="s2" dir="ltr">Video call</td>
            <td class="s2" dir="ltr">Patient should able to join a telehealth call with the assigned therapist</td>
            <td class="s2" dir="ltr"></td>
            <td class="s2" dir="ltr"></td>
        </tr>
        <tr style="height: 49px">
            <td class="s1" dir="ltr">30</td>
            <td class="s2" dir="ltr">Share screen</td>
            <td class="s2" dir="ltr">Patient should able to share the screen of mobile app using &#39;Share&#39;
                option.
            </td>
            <td class="s2" dir="ltr"></td>
            <td class="s2" dir="ltr"></td>
        </tr>
        <tr style="height: 49px">
            <td class="s1" dir="ltr">31</td>
            <td class="s1" dir="ltr" rowspan="4">Games</td>
            <td class="s2" dir="ltr">Any game / goniometer</td>
            <td class="s2" dir="ltr">It should download the game from server if it&#39;s not downloaded yet.</td>
            <td class="s2" dir="ltr"></td>
            <td class="s2" dir="ltr"></td>
        </tr>
        <tr style="height: 49px">
            <td class="s1" dir="ltr">32</td>
            <td class="s2" dir="ltr" rowspan="3">Block puzzle / Candy match / Bubble shooter / Goniometer tiles</td>
            <td class="s2" dir="ltr">It should show the &#39;Video tutorial&#39; until the patient completes the first
                level of a particular game.
            </td>
            <td class="s2" dir="ltr"></td>
            <td class="s2" dir="ltr"></td>
        </tr>
        <tr style="height: 49px">
            <td class="s1" dir="ltr">33</td>
            <td class="s2" dir="ltr">Patient should be able to go to the next level after finishing the previous level
                for any of the game.
            </td>
            <td class="s2" dir="ltr"></td>
            <td class="s2" dir="ltr"></td>
        </tr>
        <tr style="height: 49px">
            <td class="s1" dir="ltr">34</td>
            <td class="s2" dir="ltr">Patient should be able to see the current level on specific game tile.</td>
            <td class="s2" dir="ltr"></td>
            <td class="s2" dir="ltr"></td>
        </tr>
        <tr style="height: 49px">
            <td class="s1" dir="ltr">35</td>
            <td class="s1" dir="ltr" rowspan="5">Profile</td>
            <td class="s2" dir="ltr" rowspan="3">Day streak</td>
            <td class="s2" dir="ltr">Day streak should increase from 0 to 1 when the patient completes the single level
                of any game.
            </td>
            <td class="s2" dir="ltr"></td>
            <td class="s2" dir="ltr"></td>
        </tr>
        <tr style="height: 49px">
            <td class="s1" dir="ltr">36</td>
            <td class="s2" dir="ltr">Day by day it should increase by 1 when a patient regularly plays the games.</td>
            <td class="s2" dir="ltr"></td>
            <td class="s2" dir="ltr"></td>
        </tr>
        <tr style="height: 49px">
            <td class="s1" dir="ltr">37</td>
            <td class="s2" dir="ltr">If the patient misses any single day, the day streak should reset to 0 and start
                from 1 onwards.
            </td>
            <td class="s2" dir="ltr"></td>
            <td class="s2" dir="ltr"></td>
        </tr>
        <tr style="height: 69px">
            <td class="s1" dir="ltr">38</td>
            <td class="s2" dir="ltr">Affected hand</td>
            <td class="s2" dir="ltr">Patient should be able to change the hand,<br>- From left to right.<br>- From right
                to left.
            </td>
            <td class="s2" dir="ltr"></td>
            <td class="s2" dir="ltr"></td>
        </tr>
        <tr style="height: 20px">
            <td class="s1" dir="ltr">39</td>
            <td class="s2" dir="ltr">Notification</td>
            <td class="s2" dir="ltr">By default, the patient should receive the notification at 6 PM.<br><br>Patient
                should be able to adjust the time of notification as per his/her convenience.
            </td>
            <td class="s2" dir="ltr"></td>
            <td class="s2" dir="ltr"></td>
        </tr>
        <tr style="height: 49px">
            <td class="s1" dir="ltr">40</td>
            <td class="s1" dir="ltr" rowspan="3">Emails</td>
            <td class="s2" dir="ltr">Registration / welcome mail</td>
            <td class="s2" dir="ltr">Patient should receive a welcome mail upon successfully registering (which is
                verifying their phone number)
            </td>
            <td class="s2" dir="ltr"></td>
            <td class="s2" dir="ltr"></td>
        </tr>
        <tr style="height: 49px">
            <td class="s1" dir="ltr">41</td>
            <td class="s2" dir="ltr">Appointment scheduled mail</td>
            <td class="s2" dir="ltr">Patient should receive the confirmation mail for scheduled appointment.</td>
            <td class="s2" dir="ltr"></td>
            <td class="s2" dir="ltr"></td>
        </tr>
        <tr style="height: 56px">
            <td class="s1" dir="ltr">42</td>
            <td class="s2" dir="ltr">Appointment reminder mail</td>
            <td class="s2" dir="ltr">Patient should receive the reminder mail 4 hours before the scheduled time.</td>
            <td class="s2" dir="ltr"></td>
            <td class="s2" dir="ltr"></td>
        </tr>
        <tr style="height: 57px">
            <td class="s1" dir="ltr">43</td>
            <td class="s1" dir="ltr">Notification</td>
            <td class="s2" dir="ltr">Reminder notification</td>
            <td class="s2" dir="ltr">Patient should receive the reminder notification 1 hour before the scheduled
                time.
            </td>
            <td class="s2" dir="ltr"></td>
            <td class="s2" dir="ltr"></td>
        </tr>
        </tbody>
    </table>
</div>
