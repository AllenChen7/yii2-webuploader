Webuploader
============
WebUploader��һ���򵥵���Html5Ϊ����FlashΪ�����ִ��ļ��ϴ���������ִ�������������ܳ�ַ���html5�����ƣ�ͬʱ�ֲ���������IE�����������ԭ����Flash����ʱ����������ʱ��ͬ���ĵ��÷�ʽ���ɹ��û�����ѡ�á�WebUploader���ô��ļ���Ƭ�����ϴ��������������ļ��ϴ�Ч�ʡ�

Installation
------------

The preferred way to install this extension is through [composer](http://getcomposer.org/download/).

Either run

```
php composer.phar require --prefer-dist iisns/yii2-webuploader "*"
```

or add

```
"iisns/yii2-webuploader": "*"
```

to the require section of your `composer.json` file.


Usage
-----

Once the extension is installed, simply use it in your code by  :

#ͼƬ�ü��ϴ�

Ϊ���ܹ�Ԥ��������Ҫ������ҪԤ���ĵط��������´��룺

```
<div class="fileupload fileupload-new">
<div class="img-preview"></div>
</div>
```

������Ҫ���֡�ѡ���ļ����ĵط����������´��룺

```
<?= \iisns\webuploader\Cropper::widget() ?>
```

#��ͼ�ϴ�

```
<?= \iisns\webuploader\MultiImage::widget() ?>
```
