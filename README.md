
## BlazeMeter Test: Recording User Login and Logout on Saucedemo

# Link To Performance Testing Results

  *Standard User (Baseline) : https://a.blazemeter.com/app/?public-token=XgzOvwmLoZTbvUGn5zX8mU8J0o0nb3L6ppiKnWh5P4MSxXnxAI#/accounts/2097690/workspaces/2172862/projects/2479638/masters/76687186/summary
  
  *Performance Glitch User  : https://a.blazemeter.com/app/?public-token=k95PGbS0t3tlpOICt6XogomHzLdsfTtthRP34ThJQrIMSJNdq7#/accounts/2097690/workspaces/2172862/projects/2479638/masters/76687365/summary

# Prerequisites
  1.BlazeMeter account
  
  2.Saucedemo login credentials (username: "standard_user"  password: "secret_sauce", username:"performance_glitch" password:"secret_sauce")

# Recording the Test

  1. Log in to your BlazeMeter account.
  2. Click on the "Create Test" button.
  3. Select "Record and Playback" as the test type.
  4. Choose "Web" as the protocol.
  5. Click "Create Test" to proceed.
  6. In the "Recorder" section, select "Chrome" as the browser.
  7. Set the recording speed to "Slow" to ensure accurate recording.
  8. Click "Start Recording" to begin the recording process.
  9. In the recording browser, navigate to <(link unavailable)>.
  10. Enter valid login credentials and click the "Login" button.
  11. Once logged in, navigate to the "Logout" button and click it.
  12. Confirm that you are logged out by verifying the login page.
  13. Click the "Stop Recording" button in BlazeMeter.

# Converting to JMX File

  1. In BlazeMeter, navigate to the "Tests" tab.
  2. Find the recorded test and click the three dots next to it.
  3. Select "Export" and choose "JMeter (JMX)" as the format.
  4. Save the JMX file to your local machine.

# Uploading and Running the Test

  1. In BlazeMeter, navigate to the "Tests" tab.
  2. Click the "Upload Test" button.
  3. Select the JMX file you exported earlier.
  4. Configure the test settings as desired (e.g., number of users, test duration).
  5. Click "Run Test" to execute the test.
     
# Analyzing the Results

  1. Once the test is complete, navigate to the "Results" tab.
  2. Review the test results, including metrics such as response times, throughput, and errors.
  3. Use the BlazeMeter dashboard to visualize and analyze the results.
  4. Identify performance bottlenecks and areas for optimization.

By following these steps, you can use BlazeMeter to record a user logging in and out on Saucedemo, convert the recording to a JMX file, and analyze the results on the BlazeMeter dashboard.
