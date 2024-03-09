# MyFirstProgramSec_0317
- 本課程屬於初階的入門課程
- 課程主要內容在簡報，此處主要是放指令和程式碼方便複製  

## 課前準備
- 練習虛擬機使用和 Linux 基本指令
- 請加入 [Discord 群組](https://discord.gg/hQYXb7RYV4)

## 證書發放標準
完成 3/17 課程的作業，並通過助教審核

## 環境
虛擬機檔案載點：[點我](https://1drv.ms/f/s!AiGk-SANRb91iB_7utC_rNRQyIN4?e=wWR2Hi)

本次課程需要以下工具，請在上課前自行安裝或直接使用我提供的虛擬機檔案

1. GNU
```
sudo apt-get update
sudo apt-get upgrade
sudo apt-get install build-essential
```
2. Radare2
```
git clone https://github.com/radareorg/radare2
sudo ./radare2/sys/install.sh
```
3. GDB-peda
```
git clone https://github.com/scwuaptx/Pwngdb.git ; cp ~/Pwngdb/.gdbinit ~/
git clone https://github.com/scwuaptx/peda.git ~/peda ; echo "source~/peda/peda.py" >> ~/.gdbinit ; cp ~/peda/.inputrc ~/
```
4. Pwntools (with Python2)
```
sudo apt install python2
sudo apt install python-pip
python2 -m pip install --upgrade pip==20.3.4
python2 -m pip install --upgrade pwntools
```
5. IDA  

安裝有問題的話嘗試以下指令
```
sudo apt install xorg-dev
sudo apt install libxcb-xinerama0
```
