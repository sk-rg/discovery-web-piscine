!#/bin/bash 

echo "this is lin1 *.*" > draft.txt
echo "2nd line :)" >> draft.txt 
cat draft.txt

cp draft.txt draft_backup.txt
mv draft_backup.txt final_report.txt

touch temporary.tmp 
rm temporary.tmp
