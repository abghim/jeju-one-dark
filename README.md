# Jeju One Dark
An elegant theme for syntax highlights and UI styles, easy to the eyes. The color palette resembles the beautiful landscape of Jeju Island, Korea.

## Sublime Text
Straightforward json configuration. Copy the scheme provided under `jeju-one-dark-sublime/` to your Packages directory, then load. I am open to publishing this on Package Control very soon.
<img width="1552" height="981" alt="image" src="https://github.com/user-attachments/assets/25b1a47a-066b-48a3-82fb-a97b283e3649" />

## Zed
Use the command palette to install as dev extension.
<img width="1552" height="981" alt="image" src="https://github.com/user-attachments/assets/e31e8e0c-c5e5-43f6-a9b9-0b1ecdd6c621" />

## VSCode
Use the command palette to install as dev extension, or drag-and-drop the vsix file. This extension was built and tested on VSCodium, a fully open-source fork build, but will be compatible.
<img width="1552" height="981" alt="image" src="https://github.com/user-attachments/assets/e1ffb1ef-333d-4964-bb1e-a9e371750c34" />

## Emacs
Copy the `.el` file under `.emacs.d/themes/` and edit `.emacs.d/init.el` or `.emacs` to load theme on startup. Specifically, add this snippet:
```
;; ~/.emacs or init.el
(add-to-list 'custom-theme-load-path
             (expand-file-name "themes" user-emacs-directory))
(load-theme 'jeju-one-dark t) 
```
<img width="1552" height="981" alt="image" src="https://github.com/user-attachments/assets/93c5b922-49bf-427f-b34a-c0093086b76d" />
