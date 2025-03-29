git switch -c feat-a main
git commit -m "add feat-a" --allow-empty
git push origin feat-a
gh pr create --fill-first --label "enhancement"
gh pr merge --merge
gh release create v0.2.1 --title "v0.2.1" --generate-notes
new1
new2