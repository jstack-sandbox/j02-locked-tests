# Contacts

### CONTACT-001 — a contact is saved with a name

**Status:** planned

a contact is saved with a name.

**Example:** an operator saves a contact named Dana Ruiz

**Example:** the contact card shows the name and email

**Failure example:** a contact with an empty name is saved

### CONTACT-002 — a contact is visible only inside its workspace

**Status:** planned

a contact is visible only inside its workspace.

**Example:** an operator lists their workspace's contacts

**Failure example:** an operator in workspace B sees a workspace A contact in the list

**Failure example:** an operator in workspace B reads a workspace A contact by its address

### CONTACT-003 — a contact stores its workspace

**Status:** planned

a contact stores its workspace.

**Example:** a saved contact carries the operator's workspace

**Example:** an operator switching workspaces sees only the new workspace's contacts

### CONTACT-004 — an email belongs to one contact per workspace

**Status:** planned

an email belongs to one contact per workspace.

**Example:** `a@@b.com` is refused

**Example:** a second contact with `dana@example.com` is refused

### CONTACT-005 — a phone number is optional

**Status:** planned

a phone number is optional.

**Example:** a contact saved with no phone is kept

### CONTACT-006 — contacts import from a CSV file

**Status:** planned

contacts import from a CSV file.

**Example:** a CSV of two contacts imports both

### CONTACT-007 — contacts list by name

**Status:** planned

contacts list by name.

**Example:** Ana Ortiz is listed before Ben Lee

### CONTACT-008 — contacts export as CSV

**Status:** planned

contacts export as CSV.

**Example:** the export holds every contact's name and email
