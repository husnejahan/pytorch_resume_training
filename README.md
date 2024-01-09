# pytorch_resume_training
  loading the state_dict and start the training with a new optimizer.
  
  Using an “adaptive” optimizer might worsen your accuracy, since the “old” optimizer had some internal states, momentum etc., while the new one will have a cold start.
  W could try to save the optimizer’s state_dict as well.
