dstat2graphs
============

dstat��CSV���O�t�@�C�����O���t�ɕϊ����܂��B

�Z�b�g�A�b�v
------------

Red Hat Enterprise Linux 5�A6�ƁA
�����̃N���[���f�B�X�g���r���[�V������Ώۂɂ��Ă��܂��B

RRDtool��Perl��RRDs���W���[�����K�v�ł��̂ŁA
Red Hat Enterprise Linux 6�ł͈ȉ��̂悤�ɂ��ăC���X�g�[�����Ă��������B
Red Hat Enterprise Linux 5�̏ꍇ��EPEL���|�W�g��������肵�Ă��������B

    # yum install rrdtool rrdtool-perl

�{�c�[���͍�ƃf�B���N�g���Ƃ��� /dev/shm �𗘗p���܂��B
�ȉ��̂悤�ɂ��č�ƃf�B���N�g�����쐬���Ă��������B
�{�c�[�����P�v�I�Ɏg�p����ꍇ�́A /etc/rc.local ��
��ƃf�B���N�g���쐬�������L�ڂ���Ȃǂ��Ă��������B

    # mkdir /dev/shm/dstat2graphs
    # chown apache:apache /dev/shm/dstat2graphs

Apache�̃h�L�������g���[�g�z���ɃX�N���v�g��z�u���Ă��������B
�X�N���v�g��z�u�����f�B���N�g���̒����� reports �f�B���N�g�����쐬���A
apache ���[�U���������݂��s�����Ԃɂ��Ă��������B

    # mkdir <document_root>/<script_dir>/reports
    # chmod 777 <document_root>/<script_dir>/reports

�X�N���v�g��z�u�����f�B���N�g�������A
����� reports �f�B���N�g�������� css img js �̊e�f�B���N�g�����쐬���A
jQuery �� Twitter Bootstrap ��z�u���Ă��������B

�E�F�u��ʂ���̎g����
----------------------

(���Ƃ�)

Perl�X�N���v�g�P�̂ł̎g����
----------------------------

(���Ƃ�)
