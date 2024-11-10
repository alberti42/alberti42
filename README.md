<div class="home"><h1 class="page-heading">Software projects</h1>
<p>Below, you find a list of projects I have been currently maintaining in my past time.</p>

<h2 id="research-tools">Research Tools</h2>

<ul>
  <li>
    <p><strong><a href="https://github.com/alberti42/jupyterlab_mapyter">JupyterLab extension for Mapyter</a></strong>: A JupyterLab extension providing syntax support for <a href="https://github.com/alberti42/mapyter">Mapyter kernel</a>. It also provides a plugin for JupyterLab for downloading plots with a button. The button is particularly convenient to save plots shown as vectorial <code class="language-plaintext highlighter-rouge">.svg</code> graphics.</p>
  </li>
  <li>
    <p><strong><a href="https://github.com/alberti42/Keynote-Progress-Bar">Keynote Progress Bar</a></strong>: This AppleScript program adds a customizable progress bar to presentations created with Apple Keynote. The progress bar is configured using commands placed in the presenter notes of your slides. This project utilizes a custom Objective-C framework, KeynoteProgressBarHelper, for generating vector graphics (PDF) images of the progress bar.</p>
  </li>
  <li>
    <p><strong><a href="https://github.com/alberti42/mapyter">Mapyter</a></strong>: A JupyterLab kernel to develop MATLAB in a notebook. The project started before Mathworks started <a href="https://de.mathworks.com/products/reference-architectures/jupyter.html">their development</a> of MATLAB kernel for JupyterLab. It offers more advanced features than those currenlty provided by the official kernel, such as the possibility to update plots live, create animations, and display progress bar (even for <code class="language-plaintext highlighter-rouge">parfor</code> loops!). Unfortunately, the documentation page is still missing.</p>
  </li>
  <li>
    <p><strong><a href="https://github.com/alberti42/Millennia-Laser-Control-App/blob/main/README.md">Millennia Laser Control App</a></strong>: Application for controlling and logging Spectra-Physics Millennia Lasers. It covers all functions provided by the app shipped originally with the laser. It also provides new features, most notably, the possibility to log multiple parameters of the laser. Moreover, it gives a feedback about the instantaneous RMS noise level of the laser (5s integration time). And it allows controlling multiple lasers when these are connected to the same computer via USB.</p>
  </li>
</ul>

<h2 id="obsidian-plugins">Obsidian Plugins</h2>

<p>These are plugins developed to improve the workflow with <a href="https://obsidian.md/">Obsidian</a> personal knowledge management system.</p>

<ul>
  <li>
    <p><strong><a href="https://github.com/alberti42/obsidian-plugins-annotations">Annotations for Obsidian Community Plugins</a></strong>: A plugin that allows users to add personal annotations to each installed plugin in Obsidian. This is particularly useful for keeping track of why certain plugins are installed and their specific use cases.</p>
  </li>
  <li>
    <p><strong><a href="https://github.com/alberti42/obsidian-bibdesk-integration">BibDesk Integration Plugin</a></strong>: A plugin that integrates the macOS BibDesk application with the PDF++ plugin in Obsidian, enabling you to manage and open PDFs associated with BibDesk entries directly from Obsidian. It works with external BibTeX files, leveraging BibDesk’s bdsk-file-<number> fields, which act as macOS bookmarks, allowing seamless file access even if files are renamed or moved.</number></p>
  </li>
  <li>
    <p><strong><a href="https://github.com/alberti42/obsidian-dataview-recent-files">Dataview Recent Files</a></strong>: A plugin visualizing a list of recently create and modified files in a fuzzy search modal in Obsidian. It extends the functionality of Obsidian Dataview plugin. The list of the recently created and modified files is determined by the frontmatter fields, rather than on the timestamp of the MarkDown file, which can change in an uncontrolled manner, especially if syncing the vault between multiple Obsidian devices. The dcumentation page is still misisng.</p>
  </li>
  <li>
    <p><strong><a href="https://github.com/alberti42/obsidian-icon-bar-manager-plugin">Icon Bar Manager</a></strong>: A plugin for hiding undesired icons in Obisdian. Many plugins install icons without offering the possibility to hide them, resulting in a cluttered interface. The plugin allows controlling the order of the few icons one wishes to use. Unfortunately, the documentation page is missing. The plugin is also quite in a alpha stage and probably only useful to expert users who can tweak it.</p>
  </li>
  <li>
    <p><strong><a href="https://github.com/alberti42/obsidian-import-attachments-plus">Import Attachments+ Plugin</a></strong>: A plugin that enhances the attachment management experience in Obsidian. It allows you to import, organize, and handle attachments (like images, documents, and other files) seamlessly within your vault.</p>
  </li>
  <li>
    <p><strong><a href="https://github.com/alberti42/obsidian-minimize-on-close">Minimize on Close</a></strong>: A plugin that minimizes the application window to the dock or taskbar when all open panes are closed. This behavior is particularly standard on macOS and can now be optionally applied across all platforms.</p>
  </li>
  <li>
    <p><strong><a href="https://github.com/alberti42/obsidian-import-attachments-plus">Recoll Search Engine Plugin for Obsidian</a></strong>: A plugin for Obsidian to search the vault using the powerful <a href="https://www.recoll.org/">Recoll Search Engine</a>.</p>
  </li>
</ul>

<h2 id="launchbar-plugins">LaunchBar plugins</h2>

<p>These are plugins developed to improve the workflow with <a href="https://www.obdev.at/products/launchbar/index.html">LaunchBar</a> personal knowledge management system.</p>

<ul>
  <li>
    <p><strong><a href="https://github.com/alberti42/Get-Recent-Adobe-Documents-For-LaunchBar">Get Adobe Recent Documents</a></strong>: A plugin for LaunchBar to display the list of the documents recently opened for the following Adobe programs <a href="https://www.adobe.com/acrobat.html">Acrobat</a>, <a href="https://www.adobe.com/products/photoshop.html">Photoshop</a>, <a href="https://www.adobe.com/products/illustrator.html">Illustrator</a>.</p>
  </li>
  <li>
    <p><strong><a href="https://github.com/alberti42/Get-Recent-Mathematica-Documents-For-LaunchBar">Get Wolfram Mathematica Recent Documents</a></strong>: A plugin for LaunchBar to display the list of the documents recently opened in <a href="https://www.wolfram.com/mathematica/">Wolfram Mathematica</a>.</p>
  </li>
</ul>

<h2 id="sublime-text-editor-plugins">Sublime Text Editor Plugins</h2>

<ul>
  <li><strong><a href="https://github.com/alberti42/Nearley.sublime-syntax">Nearly syntax highlighting for Sublime Text Editor</a></strong>: A Sublime Text syntax highlighting file for <a href="https://nearley.js.org/">Nearley</a>. Nearly is a simple, fast, and powerful parsing toolkit. The Nearley.sublime-syntax file enables Sublime Text to recognize and highlight the syntax of Nearley grammar files (<code class="language-plaintext highlighter-rouge">*.ne</code>) effectively.</li>
</ul>

<h2 id="macos-utilities">macOS Utilities</h2>

<ul>
  <li>
    <p><strong><a href="https://github.com/alberti42/SSHuttleBar">SSHuttleBar</a></strong>: This apps allows you to control the CLI utility <a href="https://github.com/sshuttle/sshuttle"><code class="language-plaintext highlighter-rouge">sshuttle</code></a> direclty from the macOS menu bar. Thereby, one can emulate the functionality of a VPN by leveraging SSH connections. The program works, but the documentation is still missing. It integrates with 1Password SSH agent to retrieve automatically the password of remote servers.</p>
  </li>
  <li>
    <p><strong><a href="https://github.com/alberti42/Magic-Warnings">Magic Warnings</a></strong>: A lightweight macOS app that monitors the battery levels of your Apple Magic Mouse, Trackpad, and Keyboard.</p>
  </li>
  <li>
    <p><strong><a href="https://github.com/alberti42/Volume-Control">Volume Control App</a></strong>: This app allows you to directly control the volume of Apple Music and of Spotify using <code class="language-plaintext highlighter-rouge">volume-up</code> and <code class="language-plaintext highlighter-rouge">volume-down</code> keys from your keyboard.</p>
  </li>
  <li>
    <p><strong><a href="https://github.com/alberti42/iTunes-Volume-Control">iTunes Volume Control</a></strong>: The app is discontinued and superceded by Volume Control. The reason is that iTunes does no longer exist in recent macOS versions. Also, the newer app, Volume Control, is no longer restricted to Apple Music. It also works with Spotify and a few other music players.</p>
  </li>
</ul>



  
  
</div>
