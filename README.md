# mine-the-model-celesta-2023
The objective, is to create a machine-learning model to predict the retail price of houses given tabular data like house sqft, # of toilets/rooms, and location, along with an image of the house. 
\documentclass{article}
\usepackage{pgfplots}

\begin{document}

\begin{tikzpicture}
\begin{axis}[
    ybar,
    ylabel={Number of Sales},
    xlabel={Product},
    ymin=0,
    symbolic x coords={A, B, C, D},
    xtick=data,
    nodes near coords,
    nodes near coords align={vertical},
    ]
    \addplot coordinates {(A,10) (B,12) (C,15) (D,8)};
\end{axis}
\end{tikzpicture}

\end{document}

