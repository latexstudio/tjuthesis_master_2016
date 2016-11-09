## TJUThesisLatexTemplate
 
Latex template for TJU thesis. Forked from code.google.com/p/tjuthesis.
 
Modified for the new format requirements of the 2016 Master's thesis of Tianjin University.
 
## ˵��
 
����ѧ˶ʿѧλ����LaTexģ�塣
 
ģ��Դ��code.google.com/p/tjuthesis���˰汾���ݡ�����ѧ���ڲ�ʿ��˶ʿѧλ����ͳһ��ʽ�Ĺ涨�����а棩����2016.10.24�������**ȫ���ƹ���˶ʿѧλ����**��ʽ�����޸ġ�
 
��ʿ�Լ��������͵�˶ʿѧλ�ķ��桢��ҳ�Ȳ����е�����ϸ�ڲο�������ѧ���ڲ�ʿ��˶ʿѧλ����ͳһ��ʽ�Ĺ涨�����а棩�����������޸ģ�
 
## �Ķ�
 
+ ��ҳ�޸�Ϊȫ���ƹ���˶ʿ�ĸ�ʽ
+ ��ҳ�����ı���������޸�Ϊ����Ӵ�
+ �޸�����С������Ϊ20pt�м��
+ �޸�������Ӣ�ı�����о�Ϊ1.25��
+ �޸ġ�������������������ļ�϶���Լ�һЩ��ʽ΢��
+ �޸ġ�ѧλ���İ�Ȩʹ����Ȩ�顱������ļ�϶
+ �޸���ҳ���桰ѧλ��������ǩ�����롰ǩ�����ڡ�������
+ �޸��ĵ���ʽ���½ڽ�������ҳ��ʼ
+ �޸������ּ�࣬ÿ�д��Ϊ35�������ַ�
+ �޸���Ŀ¼��ʽ
+ �޸��˸�������Ķ�ǰ�κ���
+ �ο�����bib�е�����������Ҫע�����language��Ŀ���ǿվͿ��ԣ���Ȼ���Ĳο����׵ĸ�ʽ�᲻��ȷ��
+ �޸�documentclassΪ�����棬�½ڴ�����ҳ��ʼ
+ ������������Ŀ¼��ժҪ���޸�Ϊ������ҳ��ʼ
+ �޸�ҳ�߾ࣺ�ϣ�27.5mm����25.4mm����35.7mm���ң�27.7mm��ҳü��߽�15.0mm��ҳ�ž�߽�17.5mm
+ �ο����������޸�ΪС��
+ �ο�����Ӣ���е�et al�޸�Ϊ��б��
 
## ���ʹ��
 
#### LaTex����
 
[һ�ݲ�̫��̵� LaTeX ����](http://www.latexstudio.net/archives/6058)
 
[Documentation](http://www.latex-project.org/help/documentation/)
 
[Documentation - ShareLaTeX](https://www.sharelatex.com/learn)
 
#### �Ӿɰ汾���µ��˰汾
 
����Ѿ�ʹ����֮ǰ��latexģ�壬����ͨ�����²������Ϊ�˰汾�ĸ�ʽ��
 
1. ʹ�ô˰汾�µ������ļ��滻�����ǣ��ɰ汾��ͬ���ļ���
    + ./TJUThesis.bst
    + ./setup/format.tex
    + ./setup/package.tex
 
2. �޸��ļ�./tjumain.tex
    ���ƾɰ汾./tjumain.tex�����Ĳ��ֵĶ��`\include{body/yourchapter}`����ǰ���ĵĸ����½ڣ����ֱ�����˰汾./tjumain.tex����Ӧλ�ã�Ȼ���滻�ɰ汾��./tjumain.tex����������Ҫ����ע�͵�47�У�`\nocite{*}`��
 
3. �޸��ļ�./preface./cover.tex
    ���ɰ汾���ļ�./preface./cover.tex�ĸ���Ŀ�����⡢������ժҪ...����������˰汾��ͬ���ļ�����Ӧλ�ã�Ȼ���滻�ɰ汾��./preface./cover.tex�����ǹ���˶ʿ�����޸ģ�
 
4. ���±��롣
 
#### ����޸�
 
�����ĵ�����Щ��ʽ��û���ϸ�Ҫ������в�ͬ�����⣬�������һЩ��ʾ���ο���
 
+ �ĵ�Ҫ��˫���ӡ���Ҹ��½ڴ�����ҳ��ʼ�����˰汾��ժҪ�����桢��ҳ�ȶ�������ҳ��ʼ�����пհ׵�ż��ҳ��ҳüҳ������Ϊ�ա���Ҫ�漰���´��룺
    - `\documentclass[12pt,openright,twoside]{book}`
    - `\clearpage{\pagestyle{empty}\cleardoublepage}`
 
+ Ŀ¼ҳ��ҳüҳ���е��鷳��ò�Ƹ�ʽҪ����û��ҳüȻ���������ֵ�ҳ�롣��Ҫ�漰���´��룺
    - `\AtBeginDocument{\addtocontents{toc}{\protect\thispagestyle{only_foot}}}`
    - `\pagestyle{only_foot}`
    - `\tableofcontents`
    - `\thispagestyle{only_foot}` 

+ �ο��������Ҫ����GB/T 7714-2005���˰汾���޸�Ϊ��б���et al������Ҫע��������Ĳο����ף�google scholar�е����Ĳο����׵�bibTex���û��language��Ŀ����latex�и���language��Ŀ�Ƿ�ǿ����ж����ӡ� ���� �����ߡ� ,et al ������ˣ���Ҫ�ڲο�����bib�ļ��е�������������������"language={not_empty}"

+ ��ʽҪ��ͼƬ�����ĵļ����һ�У����Ǵ�ģ���е�����ͼƬ���ݶ���`\end{figure}`��ͨ��`\vspace{\baselineskip}`����������һ�еĿ�϶�����Կ���ȥ����һ�С�
 