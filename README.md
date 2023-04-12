gitpractice2

to create multiple files at a time
1..9 | ForEach-Object {
>> New-Item -Path <path> -Name ('fn_{0}.pdf' -f $_) -ItemType 'File'
>> }