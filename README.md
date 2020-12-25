# mask_predict

train
----
.. code-block:: shell
        python run_train_model.py --batch_size 4 --epoch 100 --lr 5e-4 --max_norm 1.0 --workers 4
        
demo
----
.. code-block:: shell
        python demo.py --model_path 'model.pt' --image_path 'data/test.jpg'
