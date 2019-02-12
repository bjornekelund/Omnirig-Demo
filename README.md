# WPF Omnirig demo app
OmniRig
Experimental WPF client for Alex VE3NEA's OmniRig. 
Intended as an educational tool and/or starting point for developing rig control applications in c#. 

This implementation does not suffer from the two common issues when accessing OmniRig from c# 
i.e. slow shutdown due to COM ports not being correctly released and the fact that events are 
raised on a worker thread rather than the main thread. 
