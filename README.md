# 换脸中文版
```
xgettext *.py -o /path/to/output/directory/<module_name>.po
msgfmt <module_name>.po -o /path/to/output/directory/<module_name>.mo

# examples:
msgfmt .\locale\zh_CN\LC_MESSAGES\gui_trans.po -o .\locale\zh_CN\LC_MESSAGES\gui_trans.mo
msgfmt .\locale\zh_CN\LC_MESSAGES\dicts_trans.po -o .\locale\zh_CN\LC_MESSAGES\dicts_trans.mo
```

## 进度
dicts_trans.po  line225