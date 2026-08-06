# GitHub Upload Guide

## 1. Create the repository

On the **Create a new repository** page, use these settings:

- **Visibility:** Public
- **Add README:** Off
- **Add .gitignore:** No `.gitignore`
- **Add license:** No license

Then click **Create repository**.

## 2. Upload the project files

1. Download and unzip the repository package.
2. Open the new GitHub repository.
3. Click **Add file** → **Upload files**.
4. Drag all files and folders from inside the extracted
   `pale-blue-macos-browser-icon` folder into the upload area.
5. In the commit message field, enter:

   ```text
   Add initial icon release
   ```

6. Keep **Commit directly to the main branch** selected.
7. Click **Commit changes**.

## 3. Create the first release

1. Open the repository's **Releases** section.
2. Click **Draft a new release**.
3. Enter the following tag:

   ```text
   v1.0.0
   ```

4. Use this release title:

   ```text
   Pale Blue macOS Browser Icon v1.0.0
   ```

5. Copy the contents of `RELEASE_NOTES_v1.0.0.md` into the release description.
6. Upload this file as the release asset:

   ```text
   dist/Pale-Blue-Browser-Icon.icns
   ```

7. Click **Publish release**.

## 4. Recommended repository topics

Add these topics to help people discover the project:

```text
macos
dock-icon
firefox
icns
custom-icon
light-blue
```
