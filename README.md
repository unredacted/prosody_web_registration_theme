Forked from: https://gitlab.com/beli3ver/Prosody-Web-Registration-Theme

# Prosody Web Registration Theme

This theme change the Layout of the ugly mod_register_web Plugin from Prosody. It uses Bootstrap for design and layout. All tables removed and replaced by divs.

## Installation

For Installation do this steps

    mkdir /etc/prosody/register-templates/ 
    cd /etc/prosody/register-templates 
    git clone https://github.com/crypto-world/prosody_web_registration_theme

Then add in the prosody config

    /etc/prosody/prosody.cfg.lua

The following lines

    -- Register Web Template files 
    register_web_template = "/etc/prosody/register-templates/prosody_web_registration_theme"
    
After a restart from prosody

    prosodyctl restart

You now have a nice looking theme
