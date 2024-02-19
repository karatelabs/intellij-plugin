<table>
    <tr>
        <td>
            <br/><a href="https://karatelabs.io"><img src="resources/karate-logo.svg" style="height:45px"/></a>
        </td>
        <td>
            <h2>Karate IntelliJ Plugin</h2>           
        </td>
        <th>
            <h3><a href="https://youtu.be/dhIigSSt_wg">:tv: <br/>&nbsp;&nbsp;&nbsp;Video&nbsp;&nbsp;&nbsp;</a></h3>
        </th>        
        <th>
            <h3><a href="https://www.karatelabs.io/pricing">:heavy_dollar_sign: <br/>&nbsp;&nbsp;Pricing&nbsp;&nbsp;</a></h3>
        </th>       
        <th>
            <h3><a href="https://plugins.jetbrains.com/plugin/19232-karate">:zap: <br/> Download</a></h3>
        </th>
        <th>
            <h3><a href="https://github.com/karatelabs/karate-intellij-plugin/issues">:octocat: <br/>&nbsp;&nbsp;&nbsp;Issues&nbsp;&nbsp;&nbsp;</a></h3>
        </th>        
    </tr>
</table>

<table>
    <tr>
        <th>PLUS</th>
        <th>PRO</th>
        <th>Enterprise</th>
    </tr>    
    <tr>
        <td>            
            <ul>
                <li>Syntax coloring</li>                
                <li>Run Feature from editor</li>
                <li>Run single Scenario / Example</li>
                <li>Run / Launch Configurations</li>
                <li>Structure / Outline view</li>
                <li>Code formatting</li>
                <li>In-IDE test results</li>
            </ul>
        </td>
        <td>
            <i>&nbsp;&nbsp;&nbsp;&nbsp;(includes all in PLUS)</i>
            <ul>
                <li>Auto complete</li>                
                <li>Code folding</li>
                <li>Jump to references</li>
                <li>JSON re-formatting</li>
                <li>Run all tests in folder</li>
                <li>Run Karate Labs add-ons (e.g. <a href="https://github.com/karatelabs/karate-addons/blob/main/karate-kafka/README.md">Kafka</a>)</li>
                <li>Debug Karate test</li>
                <li>Debug Java &amp; Karate in same session</li>
                <li>Java debug session stops at Karate breakpoints</li>
                <li>cURL import *</li>
                <li>OpenAPI support *</li>
            </ul><i>&nbsp;&nbsp;&nbsp;&nbsp;[*] coming soon</i>
        </td>
        <td>
            <ul>
                <li>Priority support</li>
                <li>SSO / SAML support</li>
                <li>Offline license</li>
                <li><a href="https://www.karatelabs.io/contact-us">Contact us</a></li>
            </ul>        
        </td>        
    </tr>
</table>

# Highlights
This plugin works fully-featured on [IntelliJ Community Edition](https://www.jetbrains.com/products/compare/?product=idea&product=idea-ce). JS support is built-in and does not require you to be running [IntelliJ IDEA Ultimate](https://www.jetbrains.com/idea/features/).

# License Activation
License activation and status is unified within the IntelliJ settings UI. Go to `Settings -> Languages & Frameworks -> Karate` and you should see something like this.

<img src="resources/sign-in.jpg" height="300px"/>

Click the `Sign In` link and you will be taken through the usual flow linked to your existing subscription details.

Once you have authenticated successfully, copy the session ID from the browser and paste it into the input-box now showing in the IntelliJ settings view. Click `Apply` to complete the sign-in.

Once signed-in you can work offline. You can always open this settings page to see how many days are left in your session.

If you need an offline license because of strict security or other restrictions in your environment, please [contact us](https://www.karatelabs.io/contact-us).

# Run From Editor
You can right-click a `*.feature` file in the explorer or within the editor and run it. An IntelliJ [run-configuration](#run-configurations) will be created which you can customize later if needed.

You can also run a single `Scenario` by right-clicking on it or using the "gutter" icon. Right-clicking on the gutter-icon also brings up the option to debug instead of run.

<img src="resources/run-scenario.jpg" height="300px"/>

You can even run a single "example" in a `Scenario Outline` by right-clicking on one of the data-rows within an `Examples` table.

<img src="resources/run-example.jpg" height="250px"/>

# Run Configurations
IntelliJ [run-configurations](https://www.jetbrains.com/help/idea/run-debug-configuration.html) are useful for being able to re-run tests with specific parameters. All the typical Karate options you need are supported, including control over the JVM parameters.

<img src="resources/run-config.jpg" height="300px"/>

# Structure View

The IntelliJ [structure view](https://www.jetbrains.com/help/idea/viewing-structure-of-a-source-file.html) is supported so you can navigate large files with ease.

<img src="resources/structure.jpg" height="300px"/>

# Code Formatting

Intellij [code-formatting](https://www.jetbrains.com/help/idea/reformat-and-rearrange-code.html) shortcuts work and even JSON within doc-string blocks will be formatted correctly.

<img src="resources/reformat.jpg" height="250px"/>

# Test Results

Test results integrate into the IntelliJ test-results view. The HTML report is one-click away.

<img src="resources/test-results.jpg" height="300px"/>

# Auto Complete

Besides the syntax validation, you have auto-complete for the most commonly used keywords.

<img src="resources/autocomplete.jpg" height="250px"/>

# Code Folding

You can collapse sections to make it easier to deal with long tests.

<img src="resources/code-folding.jpg" height="300px"/>

# References

You can click to navigate to called files. Or hover to see context. Currently this is supported for the `read()` and `Java.type()` syntax. More coming soon, including auto-complete.

<img src="resources/reference-java.jpg" height="250px"/>

# Run Folder

As a convenience, you can right-click and run a folder from the explorer view.

<img src="resources/run-folder.jpg" height="200px"/>

# Debug

You can set break-points on Karate feature files in debug mode. The Karate debugger can even step-back and hot-reload simple edits to your test. Note that the options for "Hot Reload" and "Step Back" may be hidden away in some versions of the IntelliJ UI.

<img src="resources/debug.jpg" height="600px"/>

## Debug Java from Karate

A Karate debug session will even stop at Java breakpoints.

## Debug Karate from Java

You can also start a normal Java debug session that uses the Karate `Runner` Java API but still stop at Karate breakpoints. This requires you to be using Karate version 1.5.0.RC3 or greater.

