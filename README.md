# pioneer-atar


### configure code

Externals set as ups product style:
```bash
./waf-tools/waf configure \
--boost-includes="$BOOST_INC" \
--boost-libs="$BOOST_LIB" \
--boost-mt \
--with-eigen="$EIGEN_DIR" \
--with-root="$ROOTSYS" \
--prefix=../opt
```

Externals set as Xin's style (not tested):
```bash
./waf-tools/waf configure \
--boost-includes="$WC_EXTERNALS/include" \
--boost-libs="$WC_EXTERNALS/lib" \
--boost-mt \
--with-eigen="$WC_EXTERNALS" \
--with-root="$WC_EXTERNALS" \
--prefix=../opt
```

### build and install

```bash
./waf-tools/waf -p build install
```
