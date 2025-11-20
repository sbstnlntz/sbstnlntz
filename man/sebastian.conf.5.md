<pre>
SEBASTIAN.CONF(5)              File Formats              SEBASTIAN.CONF(5)
</pre>

<h2>NAME</h2>
<p>
&nbsp;&nbsp;&nbsp;&nbsp;sebastian.conf - configuration describing defaults and preferences
</p>

<h2>FORMAT</h2>
<p>
&nbsp;&nbsp;&nbsp;&nbsp;The file uses key = value format. Lines beginning with '#' are comments.
</p>

<h2>EXAMPLE</h2>

<pre>
# Identity
name               = "Sebastian"
role               = "Full-Stack Developer"
motto              = "Crafting UI, engineering logic – running on caffeine."

# Environment
preferred_os       = "Linux"
secondary_os       = "Windows"
editor             = "VS Code"
shell              = "bash"
timezone           = "Europe/Berlin"

# Tech Focus
primary_languages  = ["C#", "Python", "JavaScript", "TypeScript", "PHP", "Dart"]
primary_frameworks = [".NET", "React", "Angular", "Django", "Flask", "Laravel", "Symfony", "Flutter"]
databases          = ["MySQL", "PostgreSQL", "MariaDB"]
tools              = ["Docker", "Git", "VS Code", "Postman", "Nginx", "Apache2", "Bash", "Cron", "systemd", "tmux", "SSH", "rsync"]

# Package Managers
package_managers   = ["npm", "pnpm", "Composer", "pip", "pipx", "dotnet-cli"]

# Working Style
work_mode          = "focused"
prefers_tests      = true
prefers_refactors  = true
communication      = "honest_and_clear"

# Energy
caffeine_level     = "medium_high"
break_interval_min = 50
</pre>

<h2>SEE ALSO</h2>
<p>
&nbsp;&nbsp;&nbsp;&nbsp;<a href="https://github.com/sbstnlntz/sbstnlntz/blob/main/man/sebastian.1.md">sebastian(1)</a> – User Commands<br>
&nbsp;&nbsp;&nbsp;&nbsp;<a href="https://github.com/sbstnlntz/sbstnlntz/blob/main/man/sebastian..md">sebastian(7)</a> – Developer philosophy<br>
&nbsp;&nbsp;&nbsp;&nbsp;<a href="https://github.com/sbstnlntz/sbstnlntz/blob/main/man/sebastian.service.8.md">sebastian.service(8)</a> – Runtime behavior and lifecycle<br>
&nbsp;&nbsp;&nbsp;&nbsp;<a href="https://github.com/sbstnlntz/sbstnlntz/blob/main/man/sebastian-cli.md">sebastian-cli</a> – Command-line help<br>
&nbsp;&nbsp;&nbsp;&nbsp;<a href="https://github.com/sbstnlntz/sbstnlntz/blob/main/man/caffeine.7.md">caffeine(7)</a> – Unofficial dependency
</p>

<h2>AUTHOR</h2>
<p>&nbsp;&nbsp;&nbsp;&nbsp;Sebastian</p>

<pre>
Sebastian 1.0                     2025                SEBASTIAN.CONF(5)
</pre>
