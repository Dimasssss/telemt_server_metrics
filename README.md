# Server Metrics 2026-03-12 20:27:17 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 52116.5 (14h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1796170
telemt_connections_bad_total 20723
telemt_handshake_timeouts_total 19693
telemt_upstream_connect_attempt_total 10123
telemt_upstream_connect_success_total 10064
telemt_upstream_connect_fail_total 59
telemt_upstream_connect_attempts_per_request{bucket="1"} 10123
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5244
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4785
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 35
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 59
telemt_me_keepalive_timeout_total 581
telemt_me_reconnect_attempts_total 16291
telemt_me_reconnect_success_total 7442
telemt_me_reader_eof_total 8053
telemt_me_idle_close_by_peer_total 8052
telemt_me_route_drop_no_conn_total 707519
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1676477
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8246
telemt_desync_full_logged_total 2126
telemt_desync_suppressed_total 6120
telemt_desync_frames_bucket_total{bucket="1_2"} 2157
telemt_desync_frames_bucket_total{bucket="3_10"} 2978
telemt_desync_frames_bucket_total{bucket="gt_10"} 3111
telemt_pool_swap_total 34
telemt_me_writer_removed_unexpected_total 7827
telemt_me_refill_failed_total 275
telemt_me_writer_restored_same_endpoint_total 7429
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 385
telemt_user_connections_total{user="hello"} 1675965
telemt_user_connections_current{user="hello"} 1124
telemt_user_octets_from_client{user="hello"} 25798729084 (24.03 GB)
telemt_user_octets_to_client{user="hello"} 577776498192 (538.10 GB)
telemt_user_unique_ips_current{user="hello"} 317
telemt_user_unique_ips_recent_window{user="hello"} 133
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 81737.1 (22h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 756968
telemt_connections_bad_total 10734
telemt_handshake_timeouts_total 30288
telemt_upstream_connect_attempt_total 20690
telemt_upstream_connect_success_total 20661
telemt_upstream_connect_fail_total 29
telemt_upstream_connect_attempts_per_request{bucket="1"} 20690
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10918
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9658
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 85
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 29
telemt_me_keepalive_timeout_total 3383
telemt_me_reconnect_attempts_total 15021
telemt_me_reconnect_success_total 14931
telemt_me_reader_eof_total 15872
telemt_me_idle_close_by_peer_total 15872
telemt_me_route_drop_no_conn_total 243280
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 682987
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2932
telemt_desync_full_logged_total 898
telemt_desync_suppressed_total 2034
telemt_desync_frames_bucket_total{bucket="1_2"} 1133
telemt_desync_frames_bucket_total{bucket="3_10"} 973
telemt_desync_frames_bucket_total{bucket="gt_10"} 826
telemt_pool_swap_total 81
telemt_me_writer_removed_unexpected_total 15084
telemt_me_writer_restored_same_endpoint_total 14922
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 153
telemt_user_connections_total{user="hello"} 684859
telemt_user_connections_current{user="hello"} 396
telemt_user_octets_from_client{user="hello"} 11649856408 (10.85 GB)
telemt_user_octets_to_client{user="hello"} 260788963547 (242.88 GB)
telemt_user_msgs_from_client{user="hello"} 6476
telemt_user_msgs_to_client{user="hello"} 18854
telemt_user_unique_ips_current{user="hello"} 113
telemt_user_unique_ips_recent_window{user="hello"} 55
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 81736.9 (22h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1564041
telemt_connections_bad_total 7537
telemt_handshake_timeouts_total 107014
telemt_upstream_connect_attempt_total 19192
telemt_upstream_connect_success_total 19186
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 19192
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10323
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8790
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 68
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_keepalive_timeout_total 1202
telemt_me_reconnect_attempts_total 15991
telemt_me_reconnect_success_total 14744
telemt_me_reader_eof_total 15560
telemt_me_idle_close_by_peer_total 15559
telemt_me_route_drop_no_conn_total 517297
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1205717
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4811
telemt_desync_full_logged_total 1480
telemt_desync_suppressed_total 3331
telemt_desync_frames_bucket_total{bucket="1_2"} 763
telemt_desync_frames_bucket_total{bucket="3_10"} 1740
telemt_desync_frames_bucket_total{bucket="gt_10"} 2308
telemt_pool_swap_total 73
telemt_me_writer_removed_unexpected_total 14883
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 14703
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 139
telemt_user_connections_total{user="hello"} 1205325
telemt_user_connections_current{user="hello"} 589
telemt_user_octets_from_client{user="hello"} 19047612504 (17.74 GB)
telemt_user_octets_to_client{user="hello"} 449625903813 (418.75 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 189
telemt_user_unique_ips_recent_window{user="hello"} 88
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 81737.6 (22h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 960909
telemt_connections_bad_total 12970
telemt_handshake_timeouts_total 70603
telemt_upstream_connect_attempt_total 20860
telemt_upstream_connect_success_total 20778
telemt_upstream_connect_fail_total 82
telemt_upstream_connect_attempts_per_request{bucket="1"} 20860
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11634
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9130
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 82
telemt_me_keepalive_timeout_total 1670
telemt_me_reconnect_attempts_total 24427
telemt_me_reconnect_success_total 16700
telemt_me_reader_eof_total 17841
telemt_me_idle_close_by_peer_total 17841
telemt_me_route_drop_no_conn_total 342734
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 833709
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1763
telemt_desync_full_logged_total 589
telemt_desync_suppressed_total 1174
telemt_desync_frames_bucket_total{bucket="1_2"} 500
telemt_desync_frames_bucket_total{bucket="3_10"} 679
telemt_desync_frames_bucket_total{bucket="gt_10"} 584
telemt_pool_swap_total 67
telemt_me_writer_removed_unexpected_total 17077
telemt_me_refill_failed_total 239
telemt_me_writer_restored_same_endpoint_total 16679
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_me_writer_removed_unexpected_minus_restored_total 377
telemt_user_connections_total{user="hello"} 833059
telemt_user_connections_current{user="hello"} 399
telemt_user_octets_from_client{user="hello"} 13027406808 (12.13 GB)
telemt_user_octets_to_client{user="hello"} 341160264008 (317.73 GB)
telemt_user_unique_ips_current{user="hello"} 129
telemt_user_unique_ips_recent_window{user="hello"} 63
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 81737.4 (22h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1079027
telemt_connections_bad_total 12369
telemt_handshake_timeouts_total 8939
telemt_upstream_connect_attempt_total 25432
telemt_upstream_connect_success_total 25122
telemt_upstream_connect_fail_total 310
telemt_upstream_connect_attempts_per_request{bucket="1"} 25432
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12819
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12166
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 129
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 310
telemt_me_keepalive_timeout_total 1420
telemt_me_reconnect_attempts_total 32065
telemt_me_reconnect_success_total 21027
telemt_me_reader_eof_total 22092
telemt_me_idle_close_by_peer_total 22092
telemt_me_seq_mismatch_total 33
telemt_me_route_drop_no_conn_total 403757
telemt_me_route_drop_channel_closed_total 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 990106
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 37
telemt_me_hardswap_pending_ttl_expired_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 3692
telemt_desync_full_logged_total 1292
telemt_desync_suppressed_total 2400
telemt_desync_frames_bucket_total{bucket="1_2"} 1054
telemt_desync_frames_bucket_total{bucket="3_10"} 1223
telemt_desync_frames_bucket_total{bucket="gt_10"} 1415
telemt_pool_swap_total 38
telemt_me_writer_removed_unexpected_total 21611
telemt_me_refill_failed_total 342
telemt_me_writer_restored_same_endpoint_total 20983
telemt_me_writer_restored_fallback_total 44
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 584
telemt_user_connections_total{user="hello"} 989975
telemt_user_connections_current{user="hello"} 466
telemt_user_octets_from_client{user="hello"} 12358302968 (11.51 GB)
telemt_user_octets_to_client{user="hello"} 345011129100 (321.32 GB)
telemt_user_unique_ips_current{user="hello"} 149
telemt_user_unique_ips_recent_window{user="hello"} 62
```