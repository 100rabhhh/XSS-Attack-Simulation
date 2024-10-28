<h1>🛡️ XSS Attack Simulation 🕵️‍♂️</h1>

<h2>📋 Introduction</h2>
<p>This project involves simulating a <strong>Cross-Site Scripting (XSS)</strong> attack using the <strong>Damn Vulnerable Web Application (DVWA)</strong>. The goal is to understand how XSS attacks can exploit client-side code injection vulnerabilities in web applications.</p>

<h2>🛠️ Steps & Outputs</h2>
<ol>
    <li><strong>Download & Setup:</strong>
        <ul>
            <li>🖥️ Install <strong>XAMPP</strong> and run <strong>MySQL</strong> and <strong>Apache Server</strong>.</li>
            <li>📦 Download <strong>DVWA</strong> in ZIP form, extract it, and move the folder to <code>C:/xampp/htdocs/</code>.</li>
            <li>🛠️ Rename the <code>config.inc.php</code> file in the <strong>DVWA</strong> folder and set the username to <code>'root'</code> and password to <code>''</code>.</li>
            <li>🌐 Open <code>localhost/DVWA/setup.php</code> in a browser and click <strong>'create/reset DB'</strong>.</li>
        </ul>
    </li>
    <li><strong>Login to DVWA:</strong>
        <ul>
            <li>🔑 Username: <code>admin</code> | Password: <code>password</code></li>
            <li>⚙️ Change <strong>DVWA security level</strong> to <strong>'low'</strong> for testing.</li>
        </ul>
    </li>
    <li><strong>Perform XSS Attacks:</strong>
        <ul>
            <li>🚨 Simulate 5 different XSS attacks, such as:</li>
            <li><code>&lt;IMG SRC="javascript:alert('XSS')"&gt;</code></li>
            <li><code>&lt;iframe src=%(scriptlet)s &lt;</code></li>
            <li><code>&lt;SCRIPT&gt;alert("XSS")&lt;/SCRIPT&gt;</code></li>
        </ul>
    </li>
</ol>

<h2>📊 Expected Output</h2>
<p>By injecting scripts, observe how the browser responds to various XSS inputs. The results demonstrate potential weaknesses in web application security.</p>

<h2>🧠 Conclusion</h2>
<p>This project shows the risks of <strong>XSS attacks</strong> and highlights the importance of proper <strong>input validation</strong> and <strong>sanitization</strong> to secure web applications. 🔒</p>
<h2>👥 Credits</h2>
    <p>Built by <a href="https://github.com/100rabhhh">Sourabh Jha</a></p>
    <h2>📄 License</h2>
    <p>This project is licensed under the MIT License.</p>
