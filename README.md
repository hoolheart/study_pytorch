# PyTorch Study

## Prepare

```shell
conda create -n pytorch python=3.9
conda activate pytorch
conda install pytorch torchvision torchaudio -c pytorch
conda install ipykernel matplotlib
python -m ipykernel install --user --name pytorch
```

For the platform with CUDA 11.6 (lastest on Aug 21, 2022),
the third line should be

```powershell
conda install pytorch torchvision torchaudio cudatoolkit=11.6 -c pytorch -c conda-forge
```
