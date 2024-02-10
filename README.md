# VK for desktop

VK for desktop is the same Vkontakte but for Windows as desktop application

VK Desktop — это тот же Вконтакте, но для Windows в виде компьютерного приложения



VK Desktop is an excellent way to stay connected to your Vkontakte account without having to use a web browser. The direct access client is easy to install and use, and provides a convenient way to manage your VK feed and music. It allows you to view posts, photos, groups, and other materials without any restrictions and no need of VPN. It's a great way to stay connected and up to date with your friends.

VK Desktop — отличный способ оставаться на связи с вашей учетной записью Вконтакте без использования веб-браузера. Клиент прямого доступа прост в установке и использовании и предоставляет удобный способ управления вашей лентой ВКонтакте и музыкой. Он позволяет просматривать посты, фотографии, группы и другие материалы без каких-либо ограничений и без необходимости использования VPN. Это отличный способ оставаться на связи и быть в курсе событий с друзьями.



VK desktop works on Windos 7, Widows 8, Windows 10, Windows 11.

VK desktop работает на Windows 7, Windows 8, Windows 10, Windows 11.



What are you waiting for? Hit Download and open up VK App on your Windows platform Desktop or Laptop.

Чего же ты ждешь? Нажми загрузить и открой приложение ВКонтакте на рабочем столе или ноутбуке на платформе Windows.

## Installation

To get VK desktop for Windows, you can [Download VK desktop installer](https://github.com/OlegMatuykin/vk-desktop/releases/download/v1.0.0/VK.desktop.install.exe).

Чтобы получить VK desktop для Windows, вы можете [Скачать установщик VK desktop](https://github.com/OlegMatuykin/vk-desktop/releases/download/v1.0.0/VK.desktop.install.exe).


Or you can check the [releases](https://github.com/OlegMatuykin/vk-desktop/releases) page.

## Usage

Run the "VK.desktop.install.exe" and follow installation instructions.

## For professionals

3.   You can build whole application from source code. For that you will need:
     - Visual studio 2019 with support to build .NET Framework 4.6
     - If you would like to create such installer as in release, you will need NSIS 2.5.1.

Run Developer Command Prompt for VS 2019

Execute commands in this prompt:

```
msbuild "VK desktop\VK desktop.sln" /p:Configuration=Release /p:SelfContained=True /p:PackageAsSingleFile=true /t:Publish /p:PublishDir=Publish

makensis installer_script.nsi
```


## Contributing

Pull requests are welcome. For major changes, please open an issue first
to discuss what you would like to change.
