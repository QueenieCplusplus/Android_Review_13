# Android_Review_13
RecyclerView 循環目錄清單

1. see codeScript as below. It is corresponding with UI https://github.com/QueenieCplusplus/Android_Review_9 

            // go to app/src/main/java...../katesvideoapp/ui/Fragment.kt

            package com.example.android.katesvideoapp/ui

            [default module]

            [dataBind module]
            import com.example.android.katesvideoapp.R
            import com.example.android.katesvideoapp.databinding.KatesVideoAppItemBinding
            import com.example.android.katesvideoapp.databinding.FragmentKatesVideoAppBinding

            [intent module]
            import android.content.Intent

            [view module]
            import android.view.View


            [inflater module]
            import android.view.LayoutInflater
            import androidx.fragment.app.Fragment
            import android.view.ViewGroup

            [annotation module]
            import androidx.annotation.LayoutRes

            [Uri module]
            import android.net.Uri

            [observer module]
            import androidx.lifecycle.Observer

            [viewModel module]
            import androidx.lifecycle.viewModelProvider

            [recyclerView module]
            import androidx.recyclerview.widget.RecyclerView
            import androidx.recyclerview.widge.LinearLayout

            [data modules]
            import com.example.andorid.katesvideoapp.viewmodels.ViewModel
            import com.example.android.katesvideoapp.domain.Video


             // 定義碎片畫面的類別
            class KatesVideoAppFragment: Fragment(){



                    // TODO:
                    // declair and define val ViewModel 此客製化類別的實例 
                    // declair and define val by lazy in its body 利用懶加載初始化內部唯讀資料

                    // TODO:
                    // declair and define 適配器變數可空


                    // 碎片的生命週期之一
                    override fun onViewCreated(v: View, savedInstanceState: Bundle?){

                        super.onViewCreated(v, savedInstanceState)


                    }

                    // 碎片的生命週期之一
                    override fun OnCreateView(inflater: LayoutInflater, container: ViewGroup?, savedInstanceState: Bundle?): View? {

                        // TODO：
                        // infate the fragment

                    }

                    
                    // TODO:
                    // define a private fun for remind user about the sysError such as NetworkError

             
                    // TODO:
                    // using Uri to generate Links to Youtube


            }
            
            // TODO:
            class AfterVideoClick(){
                fun onClick(v: Video) = 
            }
            
            // 定義適配器的類別。參數為上述類別的輸出。
            class VideoAdpater(val cb: AfterVideoClick): RecyclerView.Adapter<VideoViewHolder>(){
            
            
                        // TODO:
                        // declair and define the items variable.
                        
                        // TODO
                        override fun onCreateViewHolder(parent: ViewGroup, viewType: Int): VideoViewHolder{
                             
                        }
                        
                        // TODO
                        override getItemCount() = 
                        
                        // TODO
                        override fun onBindViewHolder(){
                        
                        
                        }
            
            }
            
            // 定義資料畫面目錄清單的欄位值資料抓取器
            class VideoViewHolder(val viewDataBinding: KatesVideoAppItemBinding): RecyclerView.ViewHolder(viewDataBinding.root){
            
                    companion object {
                    
                      val LAYOUT = R.layout.katesvideoapp_item
                    
                    }
            
            }
            

2. today's tip (lazy 懶加載)
