# count between two numbers
# محاسبه تعداد محصولات سالم در بین عیوب در فایل اکسل
# در مرحله اول به عنوان ورودی بک فایل اکسل حاوی تعدادی ستون از کاربر دریافت میکنیم.
# ستونی با نام WID_ACTL_PRDST میباشد که حاوی عرض محصولات است و میبایست فایل ورودی بر اساس مقادیر این ستون تفکیک شود.
# در این مرحله هر یک از فایلهای ورودی تولید شده در سلول قبل را به برنامه تحویل میدهیم و در خروجی یک فایل اکسل محاسبه شده ذخیره میشود.
# مراحل فرایند : عیوب محصول در ستون DES_REJ ذخیره شده که مقدار هر عیب تا شماره بعدی همان عیب را پیدا کرده و اختلاف آن را در ستون difference ذخیره میشود.
# در مرحله آخر فایل مرحله قبل گرفته میشود و ستون counter و مقدار خطای اولین اختلاف محاسبه شده حذف میگردد و خروجی نهایی ذخیره میشود.
