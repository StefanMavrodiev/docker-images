## lichee

This is base system configured for building lichee kernel.

### Usage

Create build directory:
```sh
mkdir android && \
cd android
```

Get sources:
* Download [lichee torrent].
* Extract into our directory:
```sh
tar -zxf /path/to/file/lichee-v3.0.tar.gz -C .
```

Pull docker image:
```sh
docker pull olimex/lichee-base
```

Run image:
```sh
docker run -i -v lichee:/Android/lichee -t olimex/lichee-base
```

### Changelog
* 12 MAR 2018
	- Initial release

[lichee torrent]: https://www.olimex.com/wiki/images/0/0c/Lichee-v3.0.torrent
