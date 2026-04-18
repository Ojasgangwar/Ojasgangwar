%-------------------------
% Resume in Latex
% Author : Ojas Gangwar
%------------------------

\documentclass[letterpaper,11pt]{article}

\usepackage[empty]{fullpage}
\usepackage{titlesec}
\usepackage{enumitem}
\usepackage[hidelinks]{hyperref}
\usepackage{fancyhdr}

\pagestyle{fancy}
\fancyhf{}
\renewcommand{\headrulewidth}{0pt}
\renewcommand{\footrulewidth}{0pt}

% Margins
\addtolength{\oddsidemargin}{-0.5in}
\addtolength{\textwidth}{1in}
\addtolength{\topmargin}{-.5in}
\addtolength{\textheight}{1.0in}

\raggedbottom
\raggedright

% Section formatting
\titleformat{\section}{
  \scshape\raggedright\large
}{}{0em}{}[\titlerule]

% Custom commands
\newcommand{\resumeSubheading}[4]{
  \item
  \begin{tabular*}{0.97\textwidth}{l@{\extracolsep{\fill}}r}
    \textbf{#1} & #2 \\
    \textit{\small#3} & \textit{\small #4}
  \end{tabular*}
}

\newcommand{\resumeItem}[1]{\item \small{#1}}

\newcommand{\resumeSubHeadingListStart}{\begin{itemize}[leftmargin=0.15in, label={}]}
\newcommand{\resumeSubHeadingListEnd}{\end{itemize}}

\newcommand{\resumeItemListStart}{\begin{itemize}[leftmargin=*]}
\newcommand{\resumeItemListEnd}{\end{itemize}}

%-------------------------------------------
%%%%%%  RESUME STARTS HERE  %%%%%%%%%%%%%%%%%%%%%%%%%%%%

\begin{document}

%----------HEADING----------
\begin{center}
    \textbf{\Huge Ojas Gangwar} \\ \vspace{5pt}
    \small 9336139917 $|$ 
    \href{mailto:ojas.study0@gmail.com}{ojas.study0@gmail.com} $|$ 
    \href{https://www.linkedin.com/in/ojas-gangwar-841b4125a}{linkedin.com/in/ojas-gangwar-841b4125a} $|$
    \href{https://ojas-gangwar-wo9a4o8.gamma.site/}{Portfolio}
\end{center}

%-----------EDUCATION-----------
\section{Education}
\resumeSubHeadingListStart
\resumeSubheading
  {Chaudhary Charan Singh University}{Meerut, UP}
  {SGPA: 8.56}{Sept. 2023 -- Present}
\resumeSubHeadingListEnd

%-----------PROJECTS-----------
\section{Projects}
\resumeSubHeadingListStart

\resumeSubheading
{Developer Portfolio – Full Stack Showcase \href{https://ojas-gangwar-wo9a4o8.gamma.site/}{(Live)}}{Feb. 2026}
{}{}
\resumeItemListStart
\resumeItem{Designed and developed a professional portfolio website showcasing full stack development projects and technical expertise}
\resumeItem{Structured sections covering backend development, frontend technologies, and project demonstrations}
\resumeItem{Highlighted Spring Boot, REST APIs, and scalable application development concepts}
\resumeItem{Focused on clean UI/UX, responsive design, and performance optimization}
\resumeItem{Live Link: \href{https://ojas-gangwar-wo9a4o8.gamma.site/}{ojas-gangwar-wo9a4o8.gamma.site}}
\resumeItemListEnd

\resumeSubheading
{PashuLens – Cattle Breed Recognition System}{Sept. 2025 -- Oct. 2025}
{}{}
\resumeItemListStart
\resumeItem{Built a Convolutional Neural Network (CNN) model achieving 85\%+ accuracy}
\resumeItem{Performed data preprocessing including resizing, normalization, and augmentation}
\resumeItem{Evaluated model using precision, recall, and confusion matrix}
\resumeItem{Integrated model into real-time prediction system}
\resumeItemListEnd

\resumeSubheading
{Rail-Yatra IRCTC Tourism Portal}{Nov. 2025 -- Dec. 2025}
{}{}
\resumeItemListStart
\resumeItem{Developed web portal using HTML, CSS, JavaScript, PHP, and MySQL}
\resumeItem{Implemented secure backend with validation and session management}
\resumeItem{Designed database architecture for efficient data handling}
\resumeItemListEnd

\resumeSubheading
{Rental Two Wheeler Service Platform}{Jan. 2026 -- Feb. 2026}
{}{}
\resumeItemListStart
\resumeItem{Developed vehicle rental system using Python}
\resumeItem{Integrated booking and backend database functionality}
\resumeItemListEnd

\resumeSubHeadingListEnd

%-----------CERTIFICATIONS-----------
\section{Certifications}
\resumeSubHeadingListStart
\resumeItem{Ethical Hacking Masterclass – Nikistian Media Pvt. Ltd.}
\resumeItem{Build With AI – GDG SCRIET}
\resumeItem{Robotics Operating System (Short Term Course)}
\resumeSubHeadingListEnd

%-----------SKILLS-----------
\section{Skills}
\begin{itemize}[leftmargin=0.15in, label={}]
\small{
\item{
\textbf{Languages:} Java, Python, JavaScript \\
\textbf{Frontend:} HTML, CSS, React \\
\textbf{Backend:} Spring Boot, PHP \\
\textbf{Database:} MySQL \\
\textbf{Tools:} GitHub, VS Code, MS Excel \\
\textbf{Core Concepts:} DSA, OOP, DBMS, OS
}
}
\end{itemize}

\end{document}
