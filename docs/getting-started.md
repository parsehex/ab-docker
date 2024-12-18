<script setup>
	import CollapseSection from './CollapseSection.vue';
</script>

# Setting Up Airbattle

## Install NVM / Node.js

First, install NVM if you haven't already. See the instructions for your operating system below:

<CollapseSection title="Windows">
Download and run the latest <code>nvm-setup.exe</code> from nvm-windows <a href="https://github.com/coreybutler/nvm-windows/releases" target="_blank">here</a>.
</CollapseSection>
<br />
<CollapseSection title="Linux/macOS">
Run <code>curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.40.1/install.sh | bash</code> in your terminal.

See full/updated instructions on <a href="https://github.com/nvm-sh/nvm#install--update-script" target="_blank">this page</a>.
</CollapseSection>

Now, install Node.js v12 by running the following commands:

```bash
nvm install 12
nvm use 12
```

## Clone the Repository

Clone this repository and its submodules, then navigate into the directory:

```bash
git clone --recursive https://github.com/parsehex/airbattle-hosting
cd airbattle-hosting
```