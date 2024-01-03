# pioneer-atar


```bash
./waf-tools/waf configure \
--boost-includes="$BOOST_INC" \
--boost-libs="$BOOST_LIB" \
--with-eigen="$EIGEN_DIR" \
--with-fftw="$FFTW_FQ_DIR" \
--with-fftw-include="$FFTW_INC" \
--with-fftw-lib="$FFTW_LIBRARY" \
--with-root="$ROOTSYS" \
--prefix=../opt
```

```
./waf-tools/waf -p build
```