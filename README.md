# Server Metrics 2026-03-11 11:17:02 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 74996.8 (20h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1678846
telemt_connections_bad_total 25368
telemt_handshake_timeouts_total 43974
telemt_upstream_connect_attempt_total 15703
telemt_upstream_connect_success_total 15694
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 15703
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7901
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7725
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 67
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 807
telemt_me_reconnect_attempts_total 24710
telemt_me_reconnect_success_total 11891
telemt_me_reader_eof_total 12864
telemt_me_idle_close_by_peer_total 12864
telemt_me_route_drop_no_conn_total 619014
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1526334
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7983
telemt_desync_full_logged_total 2157
telemt_desync_suppressed_total 5826
telemt_desync_frames_bucket_total{bucket="1_2"} 2038
telemt_desync_frames_bucket_total{bucket="3_10"} 3036
telemt_desync_frames_bucket_total{bucket="gt_10"} 2909
telemt_pool_swap_total 57
telemt_me_writer_removed_unexpected_total 12410
telemt_me_refill_failed_total 398
telemt_me_writer_restored_same_endpoint_total 11885
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 519
telemt_user_connections_total{user="hello"} 1524911
telemt_user_connections_current{user="hello"} 1327
telemt_user_octets_from_client{user="hello"} 19837673980 (18.48 GB)
telemt_user_octets_to_client{user="hello"} 434793508312 (404.93 GB)
telemt_user_unique_ips_current{user="hello"} 357
telemt_user_unique_ips_recent_window{user="hello"} 194
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 75053.7 (20h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 638725
telemt_connections_bad_total 10933
telemt_handshake_timeouts_total 39669
telemt_upstream_connect_attempt_total 24661
telemt_upstream_connect_success_total 21726
telemt_upstream_connect_fail_total 2935
telemt_upstream_connect_attempts_per_request{bucket="1"} 24661
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9951
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9532
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2034
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2935
telemt_me_keepalive_timeout_total 2184
telemt_me_reconnect_attempts_total 15861
telemt_me_reconnect_success_total 15014
telemt_me_reader_eof_total 15905
telemt_me_idle_close_by_peer_total 15903
telemt_me_route_drop_no_conn_total 259875
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 541461
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2480
telemt_desync_full_logged_total 778
telemt_desync_suppressed_total 1702
telemt_desync_frames_bucket_total{bucket="1_2"} 809
telemt_desync_frames_bucket_total{bucket="3_10"} 892
telemt_desync_frames_bucket_total{bucket="gt_10"} 779
telemt_pool_swap_total 64
telemt_me_writer_removed_unexpected_total 15201
telemt_me_refill_failed_total 22
telemt_me_writer_restored_same_endpoint_total 14992
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 187
telemt_user_connections_total{user="hello"} 543681
telemt_user_connections_current{user="hello"} 425
telemt_user_octets_from_client{user="hello"} 5604115898 (5.22 GB)
telemt_user_octets_to_client{user="hello"} 152069831156 (141.63 GB)
telemt_user_msgs_from_client{user="hello"} 7933
telemt_user_msgs_to_client{user="hello"} 11226
telemt_user_unique_ips_current{user="hello"} 128
telemt_user_unique_ips_recent_window{user="hello"} 67
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 75053.5 (20h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1109990
telemt_connections_bad_total 7814
telemt_handshake_timeouts_total 105781
telemt_upstream_connect_attempt_total 20313
telemt_upstream_connect_success_total 20064
telemt_upstream_connect_fail_total 249
telemt_upstream_connect_attempts_per_request{bucket="1"} 20313
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10942
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9025
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 97
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 249
telemt_me_keepalive_timeout_total 822
telemt_me_reconnect_attempts_total 28837
telemt_me_reconnect_success_total 15211
telemt_me_reader_eof_total 16324
telemt_me_idle_close_by_peer_total 16324
telemt_me_route_drop_no_conn_total 371945
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 955281
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2635
telemt_desync_full_logged_total 782
telemt_desync_suppressed_total 1853
telemt_desync_frames_bucket_total{bucket="1_2"} 623
telemt_desync_frames_bucket_total{bucket="3_10"} 986
telemt_desync_frames_bucket_total{bucket="gt_10"} 1026
telemt_pool_swap_total 47
telemt_me_writer_removed_unexpected_total 15832
telemt_me_refill_failed_total 422
telemt_me_writer_restored_same_endpoint_total 15200
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 621
telemt_user_connections_total{user="hello"} 956027
telemt_user_connections_current{user="hello"} 727
telemt_user_octets_from_client{user="hello"} 11141613369 (10.38 GB)
telemt_user_octets_to_client{user="hello"} 290775569017 (270.81 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 215
telemt_user_unique_ips_recent_window{user="hello"} 126
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 75054.1 (20h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 804915
telemt_connections_bad_total 70528
telemt_handshake_timeouts_total 75149
telemt_upstream_connect_attempt_total 20413
telemt_upstream_connect_success_total 20413
telemt_upstream_connect_attempts_per_request{bucket="1"} 20413
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11234
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9175
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_timeout_total 813
telemt_me_reconnect_attempts_total 17718
telemt_me_reconnect_success_total 16656
telemt_me_reader_eof_total 17688
telemt_me_idle_close_by_peer_total 17687
telemt_me_seq_mismatch_total 15
telemt_me_route_drop_no_conn_total 255222
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 636134
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 26
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1391
telemt_desync_full_logged_total 535
telemt_desync_suppressed_total 856
telemt_desync_frames_bucket_total{bucket="1_2"} 494
telemt_desync_frames_bucket_total{bucket="3_10"} 508
telemt_desync_frames_bucket_total{bucket="gt_10"} 389
telemt_pool_swap_total 68
telemt_me_writer_removed_unexpected_total 16858
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 16630
telemt_me_writer_restored_fallback_total 26
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 202
telemt_user_connections_total{user="hello"} 635501
telemt_user_connections_current{user="hello"} 487
telemt_user_octets_from_client{user="hello"} 7337459112 (6.83 GB)
telemt_user_octets_to_client{user="hello"} 181479985468 (169.02 GB)
telemt_user_unique_ips_current{user="hello"} 145
telemt_user_unique_ips_recent_window{user="hello"} 86
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 75053.9 (20h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 863630
telemt_connections_bad_total 6094
telemt_handshake_timeouts_total 8281
telemt_upstream_connect_attempt_total 20409
telemt_upstream_connect_success_total 20319
telemt_upstream_connect_fail_total 90
telemt_upstream_connect_attempts_per_request{bucket="1"} 20409
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10407
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9740
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 168
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 90
telemt_me_keepalive_timeout_total 879
telemt_me_reconnect_attempts_total 20245
telemt_me_reconnect_success_total 16442
telemt_me_reader_eof_total 17351
telemt_me_idle_close_by_peer_total 17351
telemt_me_route_drop_no_conn_total 302577
telemt_me_route_drop_channel_closed_total 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 783769
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 3259
telemt_desync_full_logged_total 1202
telemt_desync_suppressed_total 2057
telemt_desync_frames_bucket_total{bucket="1_2"} 1111
telemt_desync_frames_bucket_total{bucket="3_10"} 1292
telemt_desync_frames_bucket_total{bucket="gt_10"} 856
telemt_pool_swap_total 52
telemt_me_writer_removed_unexpected_total 16774
telemt_me_refill_failed_total 116
telemt_me_writer_restored_same_endpoint_total 16442
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 332
telemt_user_connections_total{user="hello"} 783536
telemt_user_connections_current{user="hello"} 718
telemt_user_octets_from_client{user="hello"} 11800053635 (10.99 GB)
telemt_user_octets_to_client{user="hello"} 284977302902 (265.41 GB)
telemt_user_msgs_from_client{user="hello"} 122
telemt_user_msgs_to_client{user="hello"} 215
telemt_user_unique_ips_current{user="hello"} 192
telemt_user_unique_ips_recent_window{user="hello"} 98
```