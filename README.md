# Z_Crypto_Trader
Cryptocurrency exchange trading application with low latency designed in C++ that 
trades on multiple exchanges.  I have designed a thread-safe multi-threaded application 
with sub millisecond latency utilizing thread-safe queues for lock free 
inter-thread communications.  GTK was used to develop the GUI and debugging was aided by
gdb and valgrid.  Asynchronous programming was utilized to deal with networking lags.
