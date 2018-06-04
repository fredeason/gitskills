package com.weimai.usercenter.param;


/**
 * 登入参数
 * <p>
 * Copyright (c) 2018 Choice, Inc.
 * All Rights Reserved.
 * Choice Proprietary and Confidential.
 *
 * @author shinan
 * @since 2018年05月18日
 */
public class LoginParam {
    /** 客户端: resident-居民端 doctor-医生端 weixin-居民微信端.*/
    private String client;
    /** 设备类型 ios android web.*/
    private String device;
    /** 手机号.*/
    private String phone;
    /** 各端登录额外信息.*/
    private LoginExtraParams extraParams;
    private LoginExtraParams kill;
    private LoginExtraParams redis;
    private LoginExtraParams hui;
    
    private ResidentParams residentParams;

    public String getClient() {
        return client;
    }

    public void setClient(String client) {
        this.client = client;
    }

    public String getDevice() {
        return device;
    }

    public void setDevice(String device) {
        this.device = device;
    }

    public LoginExtraParams getExtraParams() {
        return extraParams;
    }

    public void setExtraParams(LoginExtraParams extraParams) {
        this.extraParams = extraParams;
    }

    public String getPhone() {
        return phone;
    }

    public void setPhone(String phone) {
        this.phone = phone;
    }

	public ResidentParams getResidentParams() {
		return residentParams;
	}

	public void setResidentParams(ResidentParams residentParams) {
		this.residentParams = residentParams;
	}
    
    
}
