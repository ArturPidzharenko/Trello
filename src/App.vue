<template>
	<div class="container">
        <div class="row taskbar">
            <div class="col- col-sm-12 col-md-3 col-lg-3 col-xl-3">
                <div class="list-group">
                    <h2 class="list-group__name list-group__name--onhold">ON-HOLD</h2>
                    <div class="list-group__block">
                        <div href="#" class="list-group-item list-group-item-action list-group__item">
                            <div class="form-group">
                                <textarea class="form-control form-group__textarea" rows=""></textarea>
                            </div>
                            <button class="form-group__button form-group__button--close">+</button>                   
                        </div>
                        <div href="#" class="list-group-item list-group-item-action list-group__item">
                            <div class="form-group">
                                <textarea class="form-control form-group__textarea" rows=""></textarea>
                            </div>
                            <button class="form-group__button form-group__button--close">+</button>                   
                        </div>
                    </div>
                    <button class="form-group__button form-group__button--addition"><span>+</span> Добавить задачу</button> 
                </div>
            </div>
            <div class="col- col-sm-12 col-md-3 col-lg-3 col-xl-3">
                <div class="list-group">
                    <h2 class="list-group__name list-group__name--inprogress">IN-PROGRESS</h2>
                    <div class="list-group__block">
                        <div href="#" class="list-group-item list-group-item-action list-group__item">
                            <div class="form-group">
                                <textarea class="form-control form-group__textarea" rows=""></textarea>
                            </div>
                            <button class="form-group__button form-group__button--close">+</button>                   
                        </div>
                        <div href="#" class="list-group-item list-group-item-action list-group__item">
                            <div class="form-group">
                                <textarea class="form-control form-group__textarea" rows=""></textarea>
                            </div>
                            <button class="form-group__button form-group__button--close">+</button>                   
                        </div>
                        <div href="#" class="list-group-item list-group-item-action list-group__item">
                            <div class="form-group">
                                <textarea class="form-control form-group__textarea" rows=""></textarea>
                            </div>
                            <button class="form-group__button form-group__button--close">+</button>                   
                        </div>
                        <div href="#" class="list-group-item list-group-item-action list-group__item">
                            <div class="form-group">
                                <textarea class="form-control form-group__textarea" rows=""></textarea>
                            </div>
                            <button class="form-group__button form-group__button--close">+</button>                   
                        </div>
                        <div href="#" class="list-group-item list-group-item-action list-group__item">
                            <div class="form-group">
                                <textarea class="form-control form-group__textarea" rows=""></textarea>
                            </div>
                            <button class="form-group__button form-group__button--close">+</button>                   
                        </div>
                    </div>
                    <button class="form-group__button form-group__button--addition"><span>+</span> Добавить задачу</button> 
                </div>
            </div>
            <div class="col- col-sm-12 col-md-3 col-lg-3 col-xl-3">
                <div class="list-group">
                    <h2 class="list-group__name list-group__name--needsreview">NEEDS-REVIEW</h2>
                    <div class="list-group__block">
                        <div href="#" class="list-group-item list-group-item-action list-group__item">
                            <div class="form-group">
                                <textarea class="form-control form-group__textarea" rows=""></textarea>
                            </div>
                            <button class="form-group__button form-group__button--close">+</button>                   
                        </div>
                        <div href="#" class="list-group-item list-group-item-action list-group__item">
                            <div class="form-group">
                                <textarea class="form-control form-group__textarea" rows=""></textarea>
                            </div>
                            <button class="form-group__button form-group__button--close">+</button>                   
                        </div>
                    </div>
                    <button class="form-group__button form-group__button--addition"><span>+</span> Добавить задачу</button> 
                </div>
            </div>
            <div class="col- col-sm-12 col-md-3 col-lg-3 col-xl-3">
                <div class="list-group">
                    <h2 class="list-group__name list-group__name--approved">APPROVED</h2>
                    <div class="list-group__block">
                        <div href="#" class="list-group-item list-group-item-action list-group__item">
                            <div class="form-group">
                                <textarea class="form-control form-group__textarea" rows=""></textarea>
                            </div>
                            <button class="form-group__button form-group__button--close">+</button>                   
                        </div>
                        <div href="#" class="list-group-item list-group-item-action list-group__item">
                            <div class="form-group">
                                <textarea class="form-control form-group__textarea" rows=""></textarea>
                            </div>
                            <button class="form-group__button form-group__button--close">+</button>                   
                        </div>
                    </div>
                    <button class="form-group__button form-group__button--addition"><span>+</span> Добавить задачу</button> 
                </div>
            </div>
        </div>
    </div>
</template>
<script>

	export default {
		data() {
			return {
				
			}
		},
	}
</script>

<style scope>
    body {
        background: #33363d!important;      
    }

    .taskbar {
        margin-top: 50px;
        margin-bottom: 50px;
    }

    .list-group {
        margin-bottom: 40px;
        height: 90vh;
    }
    .list-group__block {
        overflow-x: hidden;
        overflow-y: auto;
    }
    .list-group__block::-webkit-scrollbar {
        height: 8px;
        width: 8px;
    }
    .list-group__block::-webkit-scrollbar-track-piece {
        background: #2b2d33;
    }
    .list-group__block::-webkit-scrollbar-thumb {
       background: white;
    }
    
    .list-group__scroll {
        overflow-y: scroll;
        overflow-x: hidden;
        height: 200px;
    }
    .list-group__name {
        font-size: 1.4rem;
        padding: 5px; 
        padding-left: 15px; 
        color: white;
        margin: 0;
    }
    .list-group__name--onhold {
        background: #fb7e46;
    }
    .list-group__name--inprogress {
        background: #2a92bf;
    }
    .list-group__name--needsreview {
        background: #f4ce46;
    }
    .list-group__name--approved {
        background: #00b961;
    }
    .list-group .list-group__item, .list-group .list-group__item:hover {
        background: #2b2d33;
    }
    .list-group__item .form-group {
        margin-bottom: 0px; 
    }
    .list-group__item .form-group:last-child {
        margin-bottom: 1rem; 
    }
    .list-group .form-group__textarea,
    .list-group .form-group__textarea:active {
        height: 100px;
        background: #1c1d20;
        color: white;
        box-shadow: none;
        border-color: transparent; 
    }
    .list-group .form-group__textarea:hover, .list-group .form-group__textarea:focus {
        border-color: white;
        background: #1c1d20;
        color: white;
        box-shadow: none;

    }
    .list-group .form-group__button {
        position: absolute;
        background: none;
        border: none;
        outline: none;
    }

    .list-group .form-group__button--close {
        right: -9px;
        top: -16px;
        color: white;
        font-weight: bold;
        transform: rotate(45deg);
        font-size: 30px;
    }

    .list-group .form-group__button--close:hover {
        color: red;
    }

    .list-group .form-group__button--addition {
        position: static;
        margin-top: -1px;
        color: white;
        font-weight: bold;
        font-size: 16px;
        z-index: 10; 
        background: #2b2d33;

    }

    .form-group__button--addition span {
        font-size: 30px;
        vertical-align: sub;
    }

    .form-group__button--addition:hover {
        color: #61bd4f;
    }

    @media (max-width: 768px) { 
        .list-group {
            height: 300px;
            margin-bottom: 50px!important;
        }
    }
		
</style>