# hPXR
 human pregnane X receptor predictions using machine learning 

# install mordred library
1. create virtual env for project:
    conda create --name hpxr
2. install mrodred:
    conda install -c rdkit -c mordred-descriptor mordred
3. install pyyaml:
    pip install pyyaml
4. install old version of networkx:
    pip install --force-reinstall networkx==2.3
5. fix deprecated .ix attribute in pandas
