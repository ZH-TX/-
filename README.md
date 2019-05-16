# -*- coding: utf-8 -*-
import pygame, sys, random, time
from pygame.locals import *  # 从pygame模块导入常用的函数和常量

# 初始化pygame，为使用硬件做准备
pygame.init()
pygame.time.Clock()
ftpsClock = pygame.time.Clock()
# 创建一个窗口aa
gamesurface = pygame.display.set_mode((980, 680))

# 设置窗口的标题
pygame.display.set_caption('tanchishe snake')
# 初始化变量
# 初始化贪吃蛇的起始位置
snakeposition = [100, 100]
# 初始化贪吃蛇的长度
snakelength = [[100, 100], [80, 100], [60, 100]]
# 初始化目标方块的位置
square_purpose = [300, 300]
# 初始化一个数来判断目标方块是否存在
square_position = 1
# 初始化方向，用来使贪吃蛇移动
derection = "right"
change_derection = derection
# 进行游戏主循环





