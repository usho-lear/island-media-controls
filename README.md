<table><tr><td align="left">
<h1>Island Media Controls</h1>
<p>Highly <strong>recommend</strong> updating to <strong>Windhawk 2.0 or later</strong> to use the redesigned settings interface.</p>
<p>Bring the current media session into the Windows 11 taskbar as a compact, clickable island. It shows the active track, artist, artwork, playback state, and progress, then expands into a larger player with seek, previous, play/pause, and next controls.</p>
</td></tr><tr><td align="left">
<h2>We are hitting 30K！</h2>
<p>It has only been four months since I discovered Windhawk and started trying to write a few mods to solve little problems of my own. Somehow, my very first mod has already reached 27K downloads. A huge thank-you to everyone who has given Island Media Controls a try—and especially those who have decided to keep it around.</p>
<p>I use this mod every day myself, so most updates really just come from my own taste and the things I want it to do. Whenever I get a new idea, I will keep working on it. I may not always be very active, but I do check my inbox and read your feedback.</p>
<blockquote><p>One small favor, though—please stop sending PRs to this media repository! Please head over to the <a href="https://windhawk.net/mods/island-media-controls">mod's Windhawk page</a> for feedback, and send code PRs to the <a href="https://github.com/ramensoftware/windhawk-mods/pulls">Windhawk mods repository</a>. I am much more likely to see them there. Thanks again, everyone!</p></blockquote>
<p>网易云音乐的适配看来是个不小的问题。就我目前测试的情况而言，它没有通过 Windows 的系统媒体会话完整提供组件所需的信息，因此高清封面和播放进度都不方便直接获取。这里涉及的是 <strong>系统媒体传输控件（SMTC）</strong>，以及本组件用来读取媒体会话的 <strong>GSMTC 接口</strong>。目前我暂时还没有可靠的解决方案；如果有大佬了解这方面，请不吝赐教了 orz。</p>
</td></tr></table>
<table><tr><th align="left"><h2>Transparent borderless</h2></th><th align="left"><h2>Transparent</h2></th></tr><tr>
<td><img src='https://raw.githubusercontent.com/usho-lear/island-media-controls/main/previews/layoutpreview/hq-0.10.234/transparent-taskbar-borderless-dark.gif' alt='Dark transparent taskbar, tint and breathing off'></td><td><img src='https://raw.githubusercontent.com/usho-lear/island-media-controls/main/previews/layoutpreview/hq-0.10.234/transparent-taskbar-bordered-dark.gif' alt='Dark transparent taskbar, tint and breathing off'></td></tr></table>
<table><tr><th colspan="3" align="left"><h2>Layout previews</h2></th></tr><tr><th align="left" width="12%"><h3>Layout</h3></th><th align="left" width="44%"><h3>Dark theme</h3></th><th align="left" width="44%"><h3>Light theme</h3></th></tr>
<tr><td align='left' valign='middle'><h3>Fullsize</h3>Glass</td><td><img src='https://raw.githubusercontent.com/usho-lear/island-media-controls/main/previews/layoutpreview/hq-0.10.234/liquid-glass-fullsize-dark.gif' alt='liquid-glass-fullsize dark'></td><td><img src='https://raw.githubusercontent.com/usho-lear/island-media-controls/main/previews/layoutpreview/hq-0.10.234/liquid-glass-fullsize-light.gif' alt='liquid-glass-fullsize light'></td></tr>
<tr><td align='left' valign='middle'><h3>Borderless</h3></td><td><img src='https://raw.githubusercontent.com/usho-lear/island-media-controls/main/previews/layoutpreview/hq-0.10.234/transparent-borderless-fullsize-dark.gif' alt='transparent-borderless-fullsize dark'></td><td><img src='https://raw.githubusercontent.com/usho-lear/island-media-controls/main/previews/layoutpreview/hq-0.10.234/transparent-borderless-fullsize-light.gif' alt='transparent-borderless-fullsize light'></td></tr>
<tr><td align='left' valign='middle'><h3>Compact</h3>Glass</td><td><img src='https://raw.githubusercontent.com/usho-lear/island-media-controls/main/previews/layoutpreview/hq-0.10.234/liquid-glass-compact-dark.gif' alt='liquid-glass-compact dark'></td><td><img src='https://raw.githubusercontent.com/usho-lear/island-media-controls/main/previews/layoutpreview/hq-0.10.234/liquid-glass-compact-light.gif' alt='liquid-glass-compact light'></td></tr>
<tr><td align='left' valign='middle'><h3>Borderless</h3></td><td><img src='https://raw.githubusercontent.com/usho-lear/island-media-controls/main/previews/layoutpreview/hq-0.10.234/transparent-borderless-compact-dark.gif' alt='transparent-borderless-compact dark'></td><td><img src='https://raw.githubusercontent.com/usho-lear/island-media-controls/main/previews/layoutpreview/hq-0.10.234/transparent-borderless-compact-light.gif' alt='transparent-borderless-compact light'></td></tr>
<tr><td align='left' valign='middle'><h3>Side</h3>Glass</td><td><img src='https://raw.githubusercontent.com/usho-lear/island-media-controls/main/previews/layoutpreview/hq-0.10.234/liquid-glass-sideexpansion-dark.gif' alt='liquid-glass-sideexpansion dark'></td><td><img src='https://raw.githubusercontent.com/usho-lear/island-media-controls/main/previews/layoutpreview/hq-0.10.234/liquid-glass-sideexpansion-light.gif' alt='liquid-glass-sideexpansion light'></td></tr>
<tr><td align='left' valign='middle'><h3>Borderless</h3></td><td><img src='https://raw.githubusercontent.com/usho-lear/island-media-controls/main/previews/layoutpreview/hq-0.10.234/transparent-borderless-sideexpansion-dark.gif' alt='transparent-borderless-sideexpansion dark'></td><td><img src='https://raw.githubusercontent.com/usho-lear/island-media-controls/main/previews/layoutpreview/hq-0.10.234/transparent-borderless-sideexpansion-light.gif' alt='transparent-borderless-sideexpansion light'></td></tr>
<tr><td align='left' valign='middle'><h3>Side · Left</h3>Glass</td><td><img src='https://raw.githubusercontent.com/usho-lear/island-media-controls/main/previews/layoutpreview/hq-0.10.234/liquid-glass-sideexpansion-left-dark.gif' alt='liquid-glass-sideexpansion-left dark'></td><td><img src='https://raw.githubusercontent.com/usho-lear/island-media-controls/main/previews/layoutpreview/hq-0.10.234/liquid-glass-sideexpansion-left-light.gif' alt='liquid-glass-sideexpansion-left light'></td></tr>
<tr><td align='left' valign='middle'><h3>Borderless</h3></td><td><img src='https://raw.githubusercontent.com/usho-lear/island-media-controls/main/previews/layoutpreview/hq-0.10.234/transparent-borderless-sideexpansion-left-dark.gif' alt='transparent-borderless-sideexpansion-left dark'></td><td><img src='https://raw.githubusercontent.com/usho-lear/island-media-controls/main/previews/layoutpreview/hq-0.10.234/transparent-borderless-sideexpansion-left-light.gif' alt='transparent-borderless-sideexpansion-left light'></td></tr>
</table>
<h2 id="whats-new">What's new</h2>
<ul>
<li><strong>Better Windows 11 taskbar integration</strong>, with an optional disc-style main island.</li>
<li><strong>More polished button styles</strong>, plus an optional experimental glass button style.</li>
<li><strong>A redesigned Compact layout</strong> that makes better use of its smaller footprint.</li>
<li><strong>Reworked materials</strong>, with richer lighting and more intuitive interaction feedback.</li>
<li><strong>Refined transition animations</strong> for opening, closing, and everyday interactions.</li>
<li><strong>A simpler, easier-to-use settings interface.</strong></li>
</ul>
<h2 id="features">Features</h2>
<ul>
<li><strong>A Dynamic Island-style media hub:</strong> Bring your current song, artwork,
progress, and playback controls into a small island on the Windows 11 taskbar.</li>
<li><strong>Multiple layout styles:</strong> Use a full expanded player, a tighter compact
player, or a side-expansion mode that reveals quick controls next to the island.</li>
<li><strong>Detailed layout customization:</strong> Adjust the island size, expanded player
size, cover behavior, background strength, button style, and animation feel to
match your setup.</li>
<li><strong>Flexible taskbar placement:</strong> Place the island near the tray, beside the
clock, or along the taskbar edge, with automatic sizing for different taskbar
heights.</li>
<li><strong>Smooth, playful animations:</strong> Hover, click, expand, collapse, play/pause,
and failed actions all respond with soft motion so the island feels alive
instead of static.</li>
<li><strong>Polished visual styles:</strong> Choose from Mica-like, Acrylic, Liquid
Glass, Transparent, and Transparent borderless materials, with album-color
highlights and refined dark/light mode treatment.</li>
<li><strong>Artwork that fits the moment:</strong> Keep original thumbnails or replace rough
browser/video artwork with generated abstract covers for a cleaner look.</li>
<li><strong>Useful playback controls:</strong> Open the player to seek through the track, switch
songs, and control playback without leaving the taskbar.</li>
</ul>
<blockquote>
<p>The island currently attaches to the primary taskbar. Taskbar placement
follows the top, bottom, left, or right edge automatically. On a vertical
taskbar, the island becomes an album button and opens toward the desktop;
Side expansion stacks its original transport buttons downward near the top
and upward near the bottom. Tray left/right and overlay
left/right correspond to top/bottom on vertical taskbars.</p>
<p>While the expanded player is open, glass and transparent materials use
Windows Graphics Capture to blur the monitor content directly behind it.
By default, the expanded player is hidden from screenshots, recordings, and
screen sharing to prevent the blur from capturing itself. Enable <strong>Expanded
player capturable blurred backdrop</strong> if it needs to appear in captures.</p>
</blockquote>
<table><tr><th colspan="3" align="left"><h2>Material previews</h2></th></tr><tr><th align="left" width="12%"><h3>Material</h3></th><th align="left" width="44%"><h3>Dark mode</h3></th><th align="left" width="44%"><h3>Light mode</h3></th></tr>
<tr><td align='left' valign='middle'><h3>Mica-like</h3></td><td><img src='https://raw.githubusercontent.com/usho-lear/island-media-controls/main/previews/materials/0.10.237/mica-dark.png' alt='Mica-like dark'></td><td><img src='https://raw.githubusercontent.com/usho-lear/island-media-controls/main/previews/materials/0.10.237/mica-light.png' alt='Mica-like light'></td></tr>
<tr><td align='left' valign='middle'><h3>Acrylic</h3></td><td><img src='https://raw.githubusercontent.com/usho-lear/island-media-controls/main/previews/materials/0.10.237/acrylic-dark.png' alt='Acrylic dark'></td><td><img src='https://raw.githubusercontent.com/usho-lear/island-media-controls/main/previews/materials/0.10.237/acrylic-light.png' alt='Acrylic light'></td></tr>
<tr><td align='left' valign='middle'><h3>Liquid Glass</h3></td><td><img src='https://raw.githubusercontent.com/usho-lear/island-media-controls/main/previews/materials/0.10.237/liquid-glass-dark.png' alt='Liquid Glass dark'></td><td><img src='https://raw.githubusercontent.com/usho-lear/island-media-controls/main/previews/materials/0.10.237/liquid-glass-light.png' alt='Liquid Glass light'></td></tr>
<tr><td align='left' valign='middle'><h3>Transparent</h3></td><td><img src='https://raw.githubusercontent.com/usho-lear/island-media-controls/main/previews/materials/0.10.237/transparent-dark.png' alt='Transparent dark'></td><td><img src='https://raw.githubusercontent.com/usho-lear/island-media-controls/main/previews/materials/0.10.237/transparent-light.png' alt='Transparent light'></td></tr>
<tr><td align='left' valign='middle'><h3>Transparent borderless</h3></td><td><img src='https://raw.githubusercontent.com/usho-lear/island-media-controls/main/previews/materials/0.10.237/transparent-borderless-dark.png' alt='Transparent borderless dark'></td><td><img src='https://raw.githubusercontent.com/usho-lear/island-media-controls/main/previews/materials/0.10.237/transparent-borderless-light.png' alt='Transparent borderless light'></td></tr>
</table>
