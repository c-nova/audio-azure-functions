# Azure Functions ���g�p���������ϊ��y�ѕ����N����

ffmpeg ���g�p���������t�@�C���̕ϊ��ƁAMicrosoft Cognitive Services Speech Service ���g�p���������N���������p�ł��܂�

* **Mp3ToWav**: �֐����� Mp3ToWav �ƂȂ��Ă���܂����A���̃t�H�[�N�ł� ffmpeg �őΉ��\�ȉ����t�@�C������ Speech Services �ŗ��p�\�� wav �t�@�C���`���ɕϊ����܂��B�ϊ��p�����[�^��ύX���邱�Ƃ��\�ł��B
* **WavToText**: SDK ���g�p���� Speech Services �ɂ�鉹�������N�������s���܂��B

## Azure �ɊȒP�f�v���C

[![Deploy to Azure](http://azuredeploy.net/deploybutton.svg)](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2F0GiS0%2Faudio-azure-functions%2Fmaster%2Fazure.deploy.json)

## �f�v���C��̐ݒ�ύX

- �Ď��ΏۃR���e�i����ύX����ɂ̓\�[�X�̕ύX���K�v�ł�
- ���[�J���ł̃e�X�g���ɂ� BLOB �̐ڑ�������Ȃǂ�ݒ肷�� local.settings.json �t�@�C�������ʓr�K�v�ł�
- �f�v���C��̓\�[�X�Ǘ����L���ɂȂ��Ă���iKUDU�܂߁j���߁A�K�v�ɉ����ĕύX���Ă�������
- �f�t�H���g�̐ݒ�ł� ffmpeg �� 32bit �̂ݗ��p�\�ł��B64bit ������ꍇ�ɂ͕ʓr���s���̕ύX���K�v�ł�

## �I���W�i���\�[�X�̏��

���̍�҂̕� (GiS) �ɂ��u���O�L���� [������](https://www.returngis.net/2018/11/azure-functions-para-procesar-mp3s-con-speech-service/) ���������������B
���̃��|�W�g���� [������](https://github.com/0GiS0/audio-azure-functions) �ɂȂ�܂��B
