# LSTM-stock-prediction
use LSTM model to predict stock

#need
import torch.nn as nn # type: ignore
import torch.optim as optim # type: ignore
import pandas as pd # type: ignore
import numpy  as np # type: ignore
import torch # type: ignore
from torch.optim import Adam # type: ignore
from torch.utils.data import DataLoader # type: ignore
import matplotlib.pyplot as plt # type: ignore
from sklearn.model_selection import train_test_split # type: ignore
from sklearn.preprocessing import MinMaxScaler # type: ignore
from torch.optim.lr_scheduler import StepLR # type: ignore
from torch.utils.tensorboard import SummaryWriter
import os
