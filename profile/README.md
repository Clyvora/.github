<div align="center">

<img src="https://raw.githubusercontent.com/ClyvoraTech/Main/main/public/favicon.png" alt="Clyvora Technologies logo" width="104">

# Clyvora Technologies

### Private by design. Useful by default.

We build focused, privacy-first browser tools that process your files on your device, not on our servers.

[Website](https://www.clyvora.tech/) | [Clyvora Lens](https://www.lens.clyvora.tech/) | [Clyvora Convert](https://www.convert.clyvora.tech/)

</div>

## Software that respects your data

Clyvora Technologies creates practical web tools without turning personal files into cloud data. There are no accounts to create and no file-upload pipeline hiding behind the interface. You can open a tool, finish the task, and leave with your data still under your control.

<table>
<tr>
<td width="50%" valign="top">

<h3 align="center">Clyvora Lens</h3>

<a href="https://www.lens.clyvora.tech/"><img src="https://raw.githubusercontent.com/ClyvoraTech/Main/main/public/lens-preview.png" alt="Clyvora Lens preview" width="100%"></a>

<p>A local-first workbench for structured data. Open JSON or CSV, inspect its contents, search and filter records, and convert between formats without sending the source file away.</p>

<strong>Features</strong>
<ul>
<li>Explore JSON as a collapsible tree or formatted text.</li>
<li>Search, sort, and filter CSV data.</li>
<li>Preview JSON and CSV conversions.</li>
<li>Process large files using browser workers.</li>
</ul>

<p><a href="https://www.lens.clyvora.tech/"><strong>Use Lens</strong></a> &middot; <a href="https://github.com/ClyvoraTech/Lens">View source</a></p>

<sub>Currently in beta. Keep a copy of important source files and verify critical output.</sub>

</td>
<td width="50%" valign="top">

<h3 align="center">Clyvora Convert</h3>

<a href="https://www.convert.clyvora.tech/"><img src="https://raw.githubusercontent.com/ClyvoraTech/Main/main/public/convert-preview.png" alt="Clyvora Convert preview" width="100%"></a>

<p>A private media converter for images, audio, and video. Files are converted locally with native browser capabilities and a self-hosted WebAssembly media engine.</p>

<strong>Features</strong>
<ul>
<li>Convert PNG, JPG, and WebP images.</li>
<li>Convert MP3, WAV, OGG, and Opus audio.</li>
<li>Convert MP4 and WebM video or extract audio.</li>
<li>Batch process files and download a ZIP.</li>
<li>Use cached conversion features offline.</li>
</ul>

<p><a href="https://www.convert.clyvora.tech/"><strong>Use Convert</strong></a> &middot; <a href="https://github.com/ClyvoraTech/Convert">View source</a></p>

</td>
</tr>
</table>

## How local-first processing works

1. **You choose a file.** The browser reads it directly from your device.
2. **The work happens locally.** Browser APIs, background workers, and WebAssembly perform the requested operation.
3. **You download the result.** The output is created on your device without passing through a Clyvora processing server.

Some explicitly requested network features, such as importing a supported public link, must contact the original media host. Each project's documentation describes these boundaries in detail.

## What we believe

- **Your files should stay yours.** File processing happens locally whenever the browser can do the work.
- **Useful tools should be simple.** No account walls, unnecessary steps, or distracting interfaces.
- **Privacy should be the default.** We design around data minimization instead of treating it as an afterthought.
- **Good software should be accessible.** Our tools are built for keyboard use, clear feedback, and reduced motion.

## Build with us

Our source-available repositories document how each tool works, how its privacy boundary is enforced, and how to run it locally. Bug reports, focused improvements, accessibility fixes, and performance work are welcome.

Before contributing, read the contributing and security guidance in the relevant repository. Licensing terms are documented per project.

<div align="center">

</div>
