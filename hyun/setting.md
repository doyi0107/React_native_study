choco설치
@"%SystemRoot%\System32\WindowsPowerShell\v1.0\powershell.exe" -NoProfile -InputFormat None -ExecutionPolicy Bypass -Command "iex ((New-Object System.Net.WebClient).DownloadString('https://chocolatey.org/install.ps1'))" && SET "PATH=%PATH%;%ALLUSERSPROFILE%\chocolatey\bin"
choco확인
choco –version

node.js설치
choco install -y nodejs.install
설치확인
node -–version
npm --version

파이썬설치
choco install -y python2
설치확인
python --version

리액트네이티브 cli설치
npm install -g react-native-cli
설치확인
npx react-native --version

jdk설치
choco install -y jdk8
설치확인
java -version
