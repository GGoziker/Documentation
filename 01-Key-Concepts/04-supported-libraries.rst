.. _key-concepts-supported-libraries:

===================
Supported Libraries
===================

|

Introduction
============

QuantConnect supports using dozens of open source packages in your algorithms. These packages are reviewed by our security team, and when approved, can be used in backtesting and live trading. To use these packages in your algorithm, you will need to add the relevant import statement at the top of your code file.

|

Library List
============

QuantConnect supports many of the most popular Python and C# open source libraries. The most popular libraries include:


The following list comes directly from the underlying docker image and is the exhaustive set of libraries supported by QuantConnect.


.. tabs::

   .. code-tab:: c#

         Accord		Newtonsoft Json.NET
         AForge		Math.Net Numerics
         AlgLib		Math.Net Filtering		RestSharp

   .. code-tab:: py

         # Name                    Version                   Build  Channel
        _libgcc_mutex             0.1                        main
        _tflow_select             2.3.0                       mkl
        absl-py                   0.9.0                    py36_0
        appdirs                   1.4.3                    pypi_0    pypi
        arch                      4.14                     pypi_0    pypi
        arviz                     0.7.0                      py_0    conda-forge
        asn1crypto                1.3.0                    py36_0
        astor                     0.8.1                    pypi_0    pypi
        astropy                   4.0.1.post1      py36h7b6447c_0
        atari-py                  0.2.6                    pypi_0    pypi
        attrs                     19.3.0                     py_0
        autograd                  1.3                      pypi_0    pypi
        backcall                  0.1.0                      py_0    conda-forge
        beautifulsoup4            4.9.0                    py36_0
        binutils_impl_linux-64    2.33.1               he6710b0_7
        binutils_linux-64         2.33.1              h9595d00_17    conda-forge
        blas                      1.0                         mkl
        blaze                     0.11.3                   py36_0
        bleach                    3.1.4              pyh9f0ad1d_0    conda-forge
        blinker                   1.4                        py_1    conda-forge
        blosc                     1.16.3               hd408876_0
        bokeh                     2.0.1                    py36_0
        boto                      2.49.0                   py36_0
        boto3                     1.9.253                  pypi_0    pypi
        botocore                  1.12.253                 pypi_0    pypi
        bottleneck                1.3.2            py36heb32a55_0
        bzip2                     1.0.8                h7b6447c_0
        c-ares                    1.15.0            h7b6447c_1001
        ca-certificates           2020.4.5.1           hecc5488_0    conda-forge
        cachetools                3.1.1                      py_0
        cairo                     1.14.12              h8948797_3
        certifi                   2020.4.5.1               py36_0
        cffi                      1.14.0           py36h2e261b9_0
        cftime                    1.1.1.2          py36h785e9b2_0    conda-forge
        chardet                   3.0.4                 py36_1003
        click                     7.1.1                      py_0
        cloudpickle               1.3.0                      py_0
        cmdstanpy                 0.4.0                    pypi_0    pypi
        cntk                      2.7                      pypi_0    pypi
        colorama                  0.4.3                    pypi_0    pypi
        colorlover                0.3.0                    pypi_0    pypi
        conda                     4.8.3            py36h9f0ad1d_1    conda-forge
        conda-env                 2.6.0                         1
        conda-package-handling    1.6.0            py36h7b6447c_0
        convertdate               2.1.3                   py_1000    conda-forge
        copulae                   0.3.1                      py_0    conda-forge
        copulalib                 1.1.0                    pypi_0    pypi
        copulas                   0.3.0                    pypi_0    pypi
        creme                     0.5.1                    pypi_0    pypi
        cryptography              2.8              py36h1ba5d50_0
        cudatoolkit               10.2.89              hfd86e86_0
        cufflinks                 0.17.3                   pypi_0    pypi
        curl                      7.69.1               h33f0ec9_0    conda-forge
        cvxopt                    1.2.0            py36hfa32c7d_0
        cvxpy                     1.1.0a3                  pypi_0    pypi
        cycler                    0.10.0                     py_2    conda-forge
        cymem                     2.0.2            py36he1b5a44_0    fastai
        cython                    0.29.15          py36he6710b0_0
        cython-blis               0.2.4            py36h516909a_1    fastai
        cytoolz                   0.10.1           py36h7b6447c_0
        dask                      2.15.0                     py_0
        dask-core                 2.15.0                     py_0
        dataclasses               0.6                      py36_0    fastai
        datashape                 0.5.4                    py36_1
        dbus                      1.13.12              h746ee38_0
        deap                      1.3.1                    pypi_0    pypi
        decorator                 4.4.2                      py_0
        defusedxml                0.6.0                      py_0    conda-forge
        dill                      0.3.1.1                  py36_0
        distributed               2.15.0                   py36_0
        docutils                  0.14                     py36_0
        dtw-python                1.0.5                    pypi_0    pypi
        ecos                      2.0.7.post1              pypi_0    pypi
        entrypoints               0.3             py36h9f0ad1d_1001    conda-forge
        ephem                     3.7.7.1          py36h516909a_0    conda-forge
        expat                     2.2.6                he6710b0_0
        exrex                     0.10.5                   pypi_0    pypi
        fastai                    1.0.60                        1    fastai
        fastprogress              0.2.2                      py_0    fastai
        fasttext                  0.9.1                    pypi_0    pypi
        fbprophet                 0.6              py36he1b5a44_0    conda-forge
        featuretools              0.13.4                     py_0    conda-forge
        flask                     1.1.2                      py_0
        flask-cors                3.0.8                      py_0
        fontconfig                2.13.0               h9420a91_0
        freetype                  2.9.1                h8a8886c_1
        fribidi                   1.0.5                h7b6447c_0
        frozendict                1.2                      pypi_0    pypi
        fsspec                    0.7.1                      py_0
        future                    0.18.2                   pypi_0    pypi
        gast                      0.2.2                    pypi_0    pypi
        gcc_impl_linux-64         7.3.0                habb00fd_1
        gcc_linux-64              7.3.0               h553295d_17    conda-forge
        gensim                    3.8.0            py36h962f231_0
        glib                      2.63.1               h5a9c865_0
        glpk                      4.65                 h3ceedfd_2
        gluonts                   0.4.3                    pypi_0    pypi
        gmp                       6.1.2                h6c8ec71_1
        google-api-core           1.16.0                   py36_1
        google-auth               1.13.1                     py_0
        google-cloud-core         1.3.0                      py_0
        google-cloud-storage      1.27.0                     py_0
        google-pasta              0.2.0                      py_0
        google-resumable-media    0.5.0                      py_1
        googleapis-common-protos  1.51.0                   py36_2
        gplearn                   0.4.1                    pypi_0    pypi
        graphite2                 1.3.13               h23475e2_0
        graphviz                  2.40.1               h21bd128_2
        grpcio                    1.28.1                   pypi_0    pypi
        gsl                       2.4                  h14c3975_4
        gst-plugins-base          1.14.0               hbbd80ab_1
        gstreamer                 1.14.0               hb453b48_1
        gxx_impl_linux-64         7.3.0                hdf63c60_1
        gxx_linux-64              7.3.0               h553295d_17    conda-forge
        gym                       0.17.1                   pypi_0    pypi
        h2o                       3.30.0.1                 pypi_0    pypi
        h5py                      2.10.0           py36h7918eee_0
        harfbuzz                  1.8.8                hffaf4a1_0
        hdf4                      4.2.13                        0    conda-forge
        hdf5                      1.10.4               hb1b8bf9_0
        heapdict                  1.0.1                      py_0
        hmmlearn                  0.2.3                    pypi_0    pypi
        holidays                  0.9.12                   pypi_0    pypi
        hypothesis                5.8.3                      py_0
        icu                       58.2                 he6710b0_3
        idna                      2.9                        py_1
        importlib_metadata        1.5.0                    py36_0
        intel-openmp              2020.0                      166
        ipykernel                 5.2.1            py36h95af2a2_0    conda-forge
        ipython                   7.13.0           py36h9f0ad1d_2    conda-forge
        ipython_genutils          0.2.0                      py_1    conda-forge
        ipywidgets                7.5.1                    pypi_0    pypi
        itsdangerous              1.1.0                    py36_0
        jax                       0.1.64                   pypi_0    pypi
        jaxlib                    0.1.45                   pypi_0    pypi
        jedi                      0.17.0           py36h9f0ad1d_0    conda-forge
        jinja2                    2.11.1                     py_0
        jmespath                  0.9.4                      py_0
        joblib                    0.14.1                     py_0
        jpeg                      9b                   h024ee3a_2
        json5                     0.9.0                      py_0    conda-forge
        jsonschema                3.2.0                    py36_0
        jupyter_client            6.1.3                      py_0    conda-forge
        jupyter_core              4.6.3            py36h9f0ad1d_1    conda-forge
        jupyterlab                2.1.0                      py_1    conda-forge
        jupyterlab_server         1.1.1                      py_0    conda-forge
        keras                     2.3.1                         0
        keras-applications        1.0.8                      py_0
        keras-base                2.3.1                    py36_0
        keras-preprocessing       1.1.0                      py_1
        keras-rl                  0.4.2                    pypi_0    pypi
        kiwisolver                1.2.0            py36hdb11119_0    conda-forge
        krb5                      1.17.1               h173b8e3_0
        ld_impl_linux-64          2.33.1               h53a641e_7
        libblas                   3.8.0                    15_mkl    conda-forge
        libcblas                  3.8.0                    15_mkl    conda-forge
        libcurl                   7.69.1               hf7181ac_0    conda-forge
        libedit                   3.1.20181209         hc058e9b_0
        libffi                    3.2.1                hd88cf55_4
        libgcc-ng                 9.1.0                hdf63c60_0
        libgfortran-ng            7.3.0                hdf63c60_0
        libgpuarray               0.7.6             h14c3975_1003    conda-forge
        libnetcdf                 4.7.3                hb80b6cc_0
        libpng                    1.6.37               hbc83047_0
        libprotobuf               3.11.4               hd408876_0
        libsodium                 1.0.17               h516909a_0    conda-forge
        libssh2                   1.8.2                h22169c7_2    conda-forge
        libstdcxx-ng              8.2.0                hdf63c60_1
        libtiff                   4.1.0                h2733197_0
        libuuid                   1.0.3                h1bed415_2
        libxcb                    1.13                 h1bed415_1
        libxml2                   2.9.9                hea5a465_1
        libxslt                   1.1.33               h7d1a2b0_0
        lightgbm                  2.3.0            py36he6710b0_0
        llvmlite                  0.30.0           py36hd408876_0
        locket                    0.2.0                    py36_1
        lunarcalendar             0.0.9                      py_0    conda-forge
        lxml                      4.5.0            py36hefd8a0e_0
        lz4-c                     1.8.1.2              h14c3975_0
        lzo                       2.10                 h7b6447c_2
        mako                      1.1.0                      py_0    conda-forge
        markdown                  3.2.1                    pypi_0    pypi
        markupsafe                1.1.1            py36h7b6447c_0
        matplotlib                3.1.1                    pypi_0    pypi
        metis                     5.1.0                hf484d3e_4
        mistune                   0.8.4           py36h8c4c3a4_1001    conda-forge
        mkl                       2020.0                      166
        mkl-service               2.3.0            py36he904b0f_0
        mkl_fft                   1.0.15           py36ha843d7b_0
        mkl_random                1.1.0            py36hd6b4f25_0
        mlfinlab                  0.9.3                    pypi_0    pypi
        mmh3                      2.5.1                    pypi_0    pypi
        mock                      4.0.1                      py_1
        more-itertools            8.2.0                      py_0
        mplfinance                0.12.3a3                 pypi_0    pypi
        msgpack-numpy             0.4.5                    pypi_0    pypi
        msgpack-python            1.0.0            py36hfd86e86_1
        multipledispatch          0.6.0                    py36_0
        murmurhash                1.0.2            py36he6710b0_0
        mxnet                     1.6.0                    pypi_0    pypi
        nbconvert                 5.6.1            py36h9f0ad1d_1    conda-forge
        nbformat                  5.0.6                      py_0    conda-forge
        ncurses                   6.2                  he6710b0_0
        netcdf4                   1.5.3            py36hbf33ddf_0
        networkx                  2.4                        py_0
        neural-tangents           0.2.1                    pypi_0    pypi
        ninja                     1.9.0            py36hfd86e86_0
        nltk                      3.4.5                    py36_0
        notebook                  6.0.3                    py36_0    conda-forge
        numba                     0.46.0           py36h962f231_0
        numexpr                   2.7.1            py36h423224d_0
        numpy                     1.18.1           py36h4f9e942_0
        numpy-base                1.18.1           py36hde5b4d6_1
        nvidia-ml-py3             7.352.0                    py_0    fastai
        oauthlib                  3.0.1                      py_0    conda-forge
        odo                       0+unknown                pypi_0    pypi
        olefile                   0.46                     py36_0
        opencv-python             4.2.0.34                 pypi_0    pypi
        openssl                   1.1.1g               h516909a_0    conda-forge
        opt-einsum                3.2.1                    pypi_0    pypi
        opt_einsum                3.1.0                      py_0
        osqp                      0.6.1                    pypi_0    pypi
        packaging                 20.3                       py_0
        pandas                    0.25.3           py36he6710b0_0
        pandoc                    2.9.2.1                       0    conda-forge
        pandocfilters             1.4.2                      py_1    conda-forge
        pango                     1.42.4               h049681c_0
        parso                     0.7.0              pyh9f0ad1d_0    conda-forge
        partd                     1.1.0                      py_0
        patsy                     0.5.1                      py_0    conda-forge
        pcre                      8.43                 he6710b0_0
        pennylane                 0.8.1                    pypi_0    pypi
        pexpect                   4.8.0            py36h9f0ad1d_1    conda-forge
        pickleshare               0.7.5           py36h9f0ad1d_1001    conda-forge
        pillow                    7.0.0            py36hb39fc2d_0
        pip                       20.0.2                   py36_1
        pixman                    0.38.0               h7b6447c_0
        plac                      0.9.6                    py36_0
        plotly                    4.6.0                      py_0    plotly
        pluggy                    0.13.1                   py36_0
        pomegranate               0.11.1           py36ha516724_0
        preshed                   2.0.1            py36he6710b0_0
        prometheus_client         0.7.1                      py_0    conda-forge
        prompt-toolkit            3.0.5                      py_0    conda-forge
        property-cached           1.6.4                    pypi_0    pypi
        protobuf                  3.11.3                   pypi_0    pypi
        psutil                    5.7.0            py36h7b6447c_0
        ptyprocess                0.6.0                   py_1001    conda-forge
        pulp                      1.6.8                 py36_1000    conda-forge
        py                        1.8.1                      py_0
        pyaml                     19.4.1                     py_0    conda-forge
        pyasn1                    0.4.8                      py_0
        pyasn1-modules            0.2.7                      py_0
        pybind11                  2.5.0                    pypi_0    pypi
        pycosat                   0.6.3            py36h7b6447c_0
        pycparser                 2.20                       py_0
        pydantic                  1.5.1                    pypi_0    pypi
        pyglet                    1.5.0                    pypi_0    pypi
        pygments                  2.6.1                      py_0    conda-forge
        pygpu                     0.7.6           py36hc1659b7_1000    conda-forge
        pyjwt                     1.7.1                      py_0    conda-forge
        pykalman                  0.9.5                    pypi_0    pypi
        pymc3                     3.8                        py_0    conda-forge
        pyopenssl                 19.1.0                   py36_0
        pyparsing                 2.4.6                      py_0
        pyportfolioopt            1.1.0                    pypi_0    pypi
        pyqt                      5.9.2            py36h05f1152_2
        pyramid-arima             0.9.0                    pypi_0    pypi
        pyrb                      1.0.1                    pypi_0    pypi
        pyro-api                  0.1.1                    pypi_0    pypi
        pyro-ppl                  1.3.1                    pypi_0    pypi
        pyrsistent                0.16.0           py36h7b6447c_0
        pysocks                   1.7.1                    py36_0
        pystan                    2.19.1.1         py36hb3f55d8_1    conda-forge
        pytables                  3.6.1            py36h71ec239_0
        pytest                    5.4.1                    py36_0
        pytest-arraydiff          0.3              py36h39e3cac_0
        pytest-astropy            0.8.0                      py_0
        pytest-astropy-header     0.1.2                      py_0
        pytest-doctestplus        0.5.0                      py_0
        pytest-openfiles          0.4.0                      py_0
        pytest-remotedata         0.3.2                    py36_0
        python                    3.6.8                h0371630_0
        python-dateutil           2.8.0                    pypi_0    pypi
        python-graphviz           0.8.4                    py36_1
        python_abi                3.6                     1_cp36m    conda-forge
        pytorch                   1.5.0           py3.6_cuda10.2.89_cudnn7.6.5_0    pytorch
        pytz                      2019.3                     py_0
        pywavelets                1.1.1            py36h785e9b2_1    conda-forge
        pyyaml                    5.3.1            py36h7b6447c_0
        pyzmq                     19.0.0           py36h9947dbf_1    conda-forge
        qt                        5.9.7                h5867ecd_1
        quadprog                  0.1.7                    pypi_0    pypi
        quantlib                  1.18                     pypi_0    pypi
        quantlib-python           1.18                     pypi_0    pypi
        rauth                     0.7.3                      py_0    conda-forge
        readline                  7.0                  h7b6447c_5
        requests                  2.23.0                   py36_0
        requests-oauthlib         1.2.0                      py_0    conda-forge
        retrying                  1.3.3                    py36_2
        riskparityportfolio       0.1.6                    pypi_0    pypi
        rsa                       4.0                        py_0
        ruamel_yaml               0.15.87          py36h7b6447c_0
        scikit-learn              0.21.3           py36hcdab131_0    conda-forge
        scikit-multiflow          0.4.1            py36h9de70de_1    conda-forge
        scikit-optimize           0.7.4                      py_0    conda-forge
        scipy                     1.4.1            py36h0b6359f_0
        scs                       2.1.2                    pypi_0    pypi
        seaborn                   0.10.1                   pypi_0    pypi
        semantic-version          2.6.0                    pypi_0    pypi
        send2trash                1.5.0                      py_0    conda-forge
        setuptools                46.1.3                   py36_0
        setuptools-git            1.2              py36h28b3542_1
        sip                       4.19.8           py36hf484d3e_0
        six                       1.14.0                   py36_0
        sklearn                   0.0                      pypi_0    pypi
        sklearn-contrib-py-earth  0.1.0                    pypi_0    pypi
        smart_open                1.11.1                     py_0
        snappy                    1.1.7                hbae5bb6_3
        sortedcontainers          2.1.0                    py36_0
        soupsieve                 2.0                        py_0
        spacy                     2.1.8            py36hc9558a2_0    fastai
        sqlalchemy                1.3.16           py36h7b6447c_0
        sqlite                    3.31.1               h62c20be_1
        srsly                     0.1.0            py36he1b5a44_0    fastai
        ssm                       0.0.1                    pypi_0    pypi
        stable-baselines          2.10.0                   pypi_0    pypi
        statistics                1.0.3.5                  pypi_0    pypi
        statsmodels               0.11.1           py36h8c4c3a4_1    conda-forge
        suitesparse               5.2.0                h9e4a6bb_0
        ta-lib                    0.4.17                   pypi_0    pypi
        tabulate                  0.8.7                    pypi_0    pypi
        tbb                       2020.0               hfd86e86_0
        tblib                     1.6.0                      py_0
        tensorboard               1.15.0             pyhb230dea_0
        tensorflow                1.15.2                   pypi_0    pypi
        tensorflow-base           1.15.0          mkl_py36he1670d9_0
        tensorflow-estimator      1.15.1             pyh2649769_0
        tensorforce               0.5.4                    pypi_0    pypi
        termcolor                 1.1.0                    pypi_0    pypi
        terminado                 0.8.3            py36h9f0ad1d_1    conda-forge
        testpath                  0.4.4                      py_0    conda-forge
        theano                    1.0.4           py36he1b5a44_1001    conda-forge
        thinc                     7.0.8            py36hc9558a2_0    fastai
        tigramite                 4.1.0                    pypi_0    pypi
        tk                        8.6.8                hbc83047_0
        toml                      0.10.0                   pypi_0    pypi
        toolz                     0.10.0                     py_0
        torchvision               0.6.0                py36_cu102    pytorch
        tornado                   6.0.4            py36h7b6447c_1
        tqdm                      4.45.0                     py_0
        traitlets                 4.3.3            py36h9f0ad1d_1    conda-forge
        tsfresh                   0.15.1                     py_0    conda-forge
        tslearn                   0.3.1            py36h785e9b2_0    conda-forge
        tweepy                    3.8.0                      py_0    conda-forge
        typing_extensions         3.7.4.1                  py36_0
        ujson                     1.35                     pypi_0    pypi
        umap-learn                0.4.1            py36h9f0ad1d_1    conda-forge
        urllib3                   1.25.8                   py36_0
        wasabi                    0.2.2                      py_0    fastai
        wcwidth                   0.1.9                      py_0
        webencodings              0.5.1                      py_1    conda-forge
        werkzeug                  0.16.1                     py_0
        wheel                     0.34.2                   py36_0
        widgetsnbextension        3.5.1                    pypi_0    pypi
        wrapt                     1.12.1           py36h7b6447c_1
        xarray                    0.15.1                     py_0
        xgboost                   1.0.2                    pypi_0    pypi
        xmlrunner                 1.7.7                    pypi_0    pypi
        xz                        5.2.5                h7b6447c_0
        yaml                      0.1.7                had09818_2
        zeromq                    4.3.2                he1b5a44_2    conda-forge
        zict                      2.0.0                      py_0
        zipp                      2.2.0                      py_0
        zlib                      1.2.11               h7b6447c_3
        zstd                      1.3.7                h0b5b093_0

|

Requesting a New Library
========================

To request a new package, please contact us at support@quantconnect.com. We will add the library to the queue for review and deployment. This process takes 2-4 weeks to be completed.