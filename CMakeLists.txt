cmake_minimum_required(VERSION 3.13)
project(Project__another_copy_)

set(CMAKE_CXX_STANDARD 14)
set(CMAKE_CXX_FLAGS -pthread)

include_directories(.)

add_executable(Project__another_copy_
        SleepCommand.cpp
        SleepCommand.h
        BinaryExpression.cpp
        BinaryExpression.h
        BindVarCommand.cpp
        BindVarCommand.h
        Command.cpp
        Command.h
        Condition.cpp
        Condition.h
        ConnectServerCommand.cpp
        ConnectServerCommand.h
        DataReaderServer.cpp
        Divide.cpp
        Divide.h
        EndCommand.cpp
        EndCommand.h
        EndLoopCommand.cpp
        EndLoopCommand.h
        Expression.cpp
        Expression.h
        GenericExpression.cpp
        GenericExpression.h
        IfCommand.cpp
        IfCommand.h
        LoopCommand.cpp
        LoopCommand.h
        main.cpp
        Minus.cpp
        Minus.h
        Multiplication.cpp
        Multiplication.h
        Number.cpp
        Number.h
        OpenServerCommand.cpp
        OpenServerCommand.h
        Plus.cpp
        Plus.h
        PrintCommand.cpp
        PrintCommand.h
        Pro.cpp
        Pro.h
        SetVarCommand.cpp
        SetVarCommand.h
        UnaryExpression.cpp
        UnaryExpression.h
        UpdateCommand.cpp
        UpdateCommand.h
        UsefulFunctions.h
        Var.cpp
        Var.h)
