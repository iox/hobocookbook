Generators -- user\_model
{: .document-title}


## Usage

    

    rails generate hobo:user_model [NAME=user] [options]


## Options

    

    -i, [--invite-only]                            # Add features for an invite only website
        [--timestamps]                             # Indicates when to generate timestamps
        [--activation-email]                       # Send an email to activate the account
        [--admin-subsite-name=ADMIN_SUBSITE_NAME]  # Admin Subsite Name
                                                   # Default: admin


## Runtime options

    

    -f, [--force]    # Overwrite files that already exist
    -s, [--skip]     # Skip files that already exist
    -p, [--pretend]  # Run but do not make any changes
    -q, [--quiet]    # Supress status output


## Description

    


      This generator is used by the user_resource generator to generate a
      user model file into app/models.

