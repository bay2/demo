# swift-vagrant

## 系统

```
No LSB modules are available.
Distributor ID: Ubuntu
Description:  Ubuntu 15.10
Release:  15.10
Codename: wily
```

## swift 版本

```
Swift version 2.2.1 (swift-2.2.1-RELEASE)
Target: x86_64-unknown-linux-gnu
```

## 使用方法

```
cd swift-vagrant
vagrant up
```

vagrant up 执行完成后

```
vagrant ssh
echo export PATH=/swift/usr/bin:"\$PATH" >> ~/.bashrc && . ~/.bashrc
```
