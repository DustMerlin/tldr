# chown

> مالک فایل یا پوشه را تغییر میدهد.
> اطلاعات بیشتر: <https://www.gnu.org/software/coreutils/manual/html_node/chown-invocation.html>.

- تغییر مالک یه فایل یا پوشه:

`chown {{user}} {{path/to/file_or_directory}}`

- تغییر کاربر و گروه مالک فایل:

`chown {{user}}:{{group}} {{path/to/file_or_directory}}`

- تغییر بازگشتی مالک یه پوشه و محتویات آن:

`chown {{[-R|--recursive]}} {{user}} {{path/to/directory}}`

- تغییر مالک یک فایل میانبر(به فایل دیگری اشاره میکند) :

`chown {{[-h|--no-dereference]}} {{user}} {{path/to/symlink}}`

- تغییر مالک یک فایل/پوشه برای همسان شدن با فایل مرجع:

`chown --reference {{path/to/reference_file}} {{path/to/file_or_directory}}`
