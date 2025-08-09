# Learn about git and github

```python
ptint('Python is the best')
```

git branch => mavjud barcha branchlarni ko'rsatadi/n
git branch branch_name => yangi branch yaratadi
git checkout/switch branch_name => mavjud bo'lgan branchga ko'chadi
git log => brachga tegishli barcha commit malumotlarni ko'rsatadi
git log --oneline => branchga tegishli barcha commitlarni har birini bir qator qilib ko'rsatadi
git checkout -b/switch -c branch_name => yangi branch yaratadi va unga ko'chadi
git branch -d branch_name => mavjud branchni o'chiradi
git merge branch_name => ikkita branchni qo'shadi

git diff --staged/file_id_one..file_id_two/branch_one..branch_two => ikki fili yoki branch orasidagi farqni ko'rsatadi

git stash => o'zgarishlarni commit qilmasdan vaqtincha saqlab qo'yadi
git stash pop => saqlangan o'zgarishlarni qo'shadi
git stash list => stashlar listi
git stash apply stash_id => saqlangan stashlardan bilini qo'shish

git checkout commit_id/HEAD~x => id si berilgan commit ga yoki x marta orqaga qaytadi 
git checkout main_branch_name(master) => eng ohirgi commit ga qaytadi

git remote -v => remote larni korish
git remote add name url => remote qo'shish
git remote rename oldname newname => remote ni qayta nomlash
git push -u remote branch => github ga push qilish va o'rtada aloqa yaratish(keyingi safardan git push ning o'zini yozish yetarli bo'lishi uchun)
git branch -M new_branch_name => branchni qayta nomlash