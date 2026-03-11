# Server Metrics 2026-03-11 20:13:07 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 107160.8 (29h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2721641
telemt_connections_bad_total 52919
telemt_handshake_timeouts_total 61553
telemt_upstream_connect_attempt_total 22629
telemt_upstream_connect_success_total 22617
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 22629
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11404
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11101
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 111
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_keepalive_timeout_total 5401
telemt_me_reconnect_attempts_total 35089
telemt_me_reconnect_success_total 17195
telemt_me_reader_eof_total 18576
telemt_me_idle_close_by_peer_total 18576
telemt_me_route_drop_no_conn_total 1025604
telemt_me_route_drop_channel_closed_total 10
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2480179
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 12567
telemt_desync_full_logged_total 3492
telemt_desync_suppressed_total 9075
telemt_desync_frames_bucket_total{bucket="1_2"} 3098
telemt_desync_frames_bucket_total{bucket="3_10"} 4834
telemt_desync_frames_bucket_total{bucket="gt_10"} 4635
telemt_pool_swap_total 76
telemt_me_writer_removed_unexpected_total 17952
telemt_me_refill_failed_total 555
telemt_me_writer_restored_same_endpoint_total 17189
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 757
telemt_user_connections_total{user="hello"} 2478531
telemt_user_connections_current{user="hello"} 981
telemt_user_octets_from_client{user="hello"} 36826702116 (34.30 GB)
telemt_user_octets_to_client{user="hello"} 708811175520 (660.13 GB)
telemt_user_unique_ips_current{user="hello"} 285
telemt_user_unique_ips_recent_window{user="hello"} 110
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 107217.6 (29h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1004039
telemt_connections_bad_total 16558
telemt_handshake_timeouts_total 90319
telemt_upstream_connect_attempt_total 32882
telemt_upstream_connect_success_total 29910
telemt_upstream_connect_fail_total 2972
telemt_upstream_connect_attempts_per_request{bucket="1"} 32882
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14160
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13457
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2084
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2972
telemt_me_keepalive_timeout_total 2880
telemt_me_reconnect_attempts_total 23668
telemt_me_reconnect_success_total 21546
telemt_me_reader_eof_total 22825
telemt_me_idle_close_by_peer_total 22822
telemt_me_route_drop_no_conn_total 379817
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 838228
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3328
telemt_desync_full_logged_total 1080
telemt_desync_suppressed_total 2248
telemt_desync_frames_bucket_total{bucket="1_2"} 1067
telemt_desync_frames_bucket_total{bucket="3_10"} 1181
telemt_desync_frames_bucket_total{bucket="gt_10"} 1080
telemt_pool_swap_total 87
telemt_me_writer_removed_unexpected_total 21863
telemt_me_refill_failed_total 60
telemt_me_writer_restored_same_endpoint_total 21523
telemt_me_writer_restored_fallback_total 23
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 317
telemt_user_connections_total{user="hello"} 840670
telemt_user_connections_current{user="hello"} 368
telemt_user_octets_from_client{user="hello"} 10132076986 (9.44 GB)
telemt_user_octets_to_client{user="hello"} 245222929144 (228.38 GB)
telemt_user_msgs_from_client{user="hello"} 7933
telemt_user_msgs_to_client{user="hello"} 11226
telemt_user_unique_ips_current{user="hello"} 115
telemt_user_unique_ips_recent_window{user="hello"} 48
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 107217.5 (29h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1740202
telemt_connections_bad_total 10869
telemt_handshake_timeouts_total 134766
telemt_upstream_connect_attempt_total 27344
telemt_upstream_connect_success_total 26998
telemt_upstream_connect_fail_total 346
telemt_upstream_connect_attempts_per_request{bucket="1"} 27344
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14630
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12230
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 137
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 346
telemt_me_keepalive_timeout_total 2011
telemt_me_reconnect_attempts_total 55704
telemt_me_reconnect_success_total 20480
telemt_me_reader_eof_total 22439
telemt_me_idle_close_by_peer_total 22439
telemt_me_route_drop_no_conn_total 633697
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1529503
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4141
telemt_desync_full_logged_total 1222
telemt_desync_suppressed_total 2919
telemt_desync_frames_bucket_total{bucket="1_2"} 968
telemt_desync_frames_bucket_total{bucket="3_10"} 1574
telemt_desync_frames_bucket_total{bucket="gt_10"} 1599
telemt_pool_swap_total 55
telemt_me_writer_removed_unexpected_total 21861
telemt_me_refill_failed_total 1095
telemt_me_writer_restored_same_endpoint_total 20468
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 1381
telemt_user_connections_total{user="hello"} 1529138
telemt_user_connections_current{user="hello"} 580
telemt_user_octets_from_client{user="hello"} 19712632089 (18.36 GB)
telemt_user_octets_to_client{user="hello"} 468611744697 (436.43 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 195
telemt_user_unique_ips_recent_window{user="hello"} 84
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 107217.9 (29h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1242562
telemt_connections_bad_total 78220
telemt_handshake_timeouts_total 111230
telemt_upstream_connect_attempt_total 28876
telemt_upstream_connect_success_total 28876
telemt_upstream_connect_attempts_per_request{bucket="1"} 28876
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15729
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13141
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 1484
telemt_me_reconnect_attempts_total 28107
telemt_me_reconnect_success_total 23489
telemt_me_reader_eof_total 24941
telemt_me_idle_close_by_peer_total 24940
telemt_me_seq_mismatch_total 23
telemt_me_route_drop_no_conn_total 417458
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1017555
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 34
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2184
telemt_desync_full_logged_total 818
telemt_desync_suppressed_total 1366
telemt_desync_frames_bucket_total{bucket="1_2"} 778
telemt_desync_frames_bucket_total{bucket="3_10"} 733
telemt_desync_frames_bucket_total{bucket="gt_10"} 673
telemt_pool_swap_total 88
telemt_me_writer_removed_unexpected_total 23880
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 23456
telemt_me_writer_restored_fallback_total 33
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 391
telemt_user_connections_total{user="hello"} 1016681
telemt_user_connections_current{user="hello"} 397
telemt_user_octets_from_client{user="hello"} 12086223580 (11.26 GB)
telemt_user_octets_to_client{user="hello"} 310981037716 (289.62 GB)
telemt_user_unique_ips_current{user="hello"} 122
telemt_user_unique_ips_recent_window{user="hello"} 63
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 11893.9 (3h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 182039
telemt_connections_bad_total 5148
telemt_handshake_timeouts_total 1934
telemt_upstream_connect_attempt_total 3448
telemt_upstream_connect_success_total 3447
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 3448
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1787
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1644
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 16
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 66
telemt_me_reconnect_attempts_total 2803
telemt_me_reconnect_success_total 2774
telemt_me_reader_eof_total 2867
telemt_me_idle_close_by_peer_total 2867
telemt_me_seq_mismatch_total 3
telemt_me_route_drop_no_conn_total 61115
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 159631
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 25
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 374
telemt_desync_full_logged_total 127
telemt_desync_suppressed_total 247
telemt_desync_frames_bucket_total{bucket="1_2"} 88
telemt_desync_frames_bucket_total{bucket="3_10"} 135
telemt_desync_frames_bucket_total{bucket="gt_10"} 151
telemt_pool_swap_total 5
telemt_me_writer_removed_unexpected_total 2807
telemt_me_writer_restored_same_endpoint_total 2749
telemt_me_writer_restored_fallback_total 25
telemt_me_async_recovery_trigger_total 256
telemt_me_writer_removed_unexpected_minus_restored_total 33
telemt_user_connections_total{user="hello"} 159597
telemt_user_connections_current{user="hello"} 519
telemt_user_octets_from_client{user="hello"} 9464681508 (8.81 GB)
telemt_user_octets_to_client{user="hello"} 53435106056 (49.77 GB)
telemt_user_unique_ips_current{user="hello"} 133
telemt_user_unique_ips_recent_window{user="hello"} 60
```