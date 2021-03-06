# releasecompare
A Bash comparison tool, which compares the latest online Manjaro release to the local system.

That way it is easy to see which applications may have been added to new releases.

The resulting files can be used to:

- Show/Install the different packages from the online release compared to the installed packages (the ``` *release.txt ``` file)

- Show/Install only new packages which have not been removed by the User  (the ``` release-removed-uninstalled.txt ``` file)

---

- The ``` userpkglist.txt ``` file can be used as a backup file of installed applications by the User.

---

For installation options run: ``` ./releasecompare install ```

To install manually run either:
- ``` sudo pacman -S - < *release.txt ```
- ```  sudo pacman -S - < release-removed-uninstalled.txt ```

---
