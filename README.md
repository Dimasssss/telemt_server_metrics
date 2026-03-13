# Server Metrics 2026-03-13 16:22:03 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 123805.5 (34h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3904900
telemt_connections_bad_total 37507
telemt_handshake_timeouts_total 91893
telemt_upstream_connect_attempt_total 23999
telemt_upstream_connect_success_total 23862
telemt_upstream_connect_fail_total 137
telemt_upstream_connect_attempts_per_request{bucket="1"} 23999
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12308
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11491
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 63
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 137
telemt_me_keepalive_timeout_total 2218
telemt_me_reconnect_attempts_total 27804
telemt_me_reconnect_success_total 17713
telemt_me_reader_eof_total 19037
telemt_me_idle_close_by_peer_total 19036
telemt_me_route_drop_no_conn_total 1449783
telemt_me_route_drop_channel_closed_total 18
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3570704
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 14193
telemt_desync_full_logged_total 3748
telemt_desync_suppressed_total 10445
telemt_desync_frames_bucket_total{bucket="1_2"} 3559
telemt_desync_frames_bucket_total{bucket="3_10"} 5374
telemt_desync_frames_bucket_total{bucket="gt_10"} 5260
telemt_pool_swap_total 104
telemt_me_writer_removed_unexpected_total 18271
telemt_me_refill_failed_total 312
telemt_me_writer_restored_same_endpoint_total 17700
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 558
telemt_user_connections_total{user="hello"} 3570507
telemt_user_connections_current{user="hello"} 1918
telemt_user_octets_from_client{user="hello"} 49419183328 (46.03 GB)
telemt_user_octets_to_client{user="hello"} 1116929585952 (1.02 TB)
telemt_user_unique_ips_current{user="hello"} 473
telemt_user_unique_ips_recent_window{user="hello"} 258
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 23469.5 (6h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 343707
telemt_connections_bad_total 21773
telemt_handshake_timeouts_total 9772
telemt_upstream_connect_attempt_total 5455
telemt_upstream_connect_success_total 5368
telemt_upstream_connect_fail_total 87
telemt_upstream_connect_attempts_per_request{bucket="1"} 5455
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2767
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2543
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 16
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 42
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 87
telemt_me_keepalive_timeout_total 120
telemt_me_reconnect_attempts_total 6445
telemt_me_reconnect_success_total 4150
telemt_me_reader_eof_total 4397
telemt_me_idle_close_by_peer_total 4397
telemt_me_route_drop_no_conn_total 124290
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 303575
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1124
telemt_desync_full_logged_total 290
telemt_desync_suppressed_total 834
telemt_desync_frames_bucket_total{bucket="1_2"} 216
telemt_desync_frames_bucket_total{bucket="3_10"} 545
telemt_desync_frames_bucket_total{bucket="gt_10"} 363
telemt_pool_swap_total 18
telemt_me_writer_removed_unexpected_total 4276
telemt_me_refill_failed_total 69
telemt_me_writer_restored_same_endpoint_total 4143
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 126
telemt_user_connections_total{user="hello"} 303604
telemt_user_connections_current{user="hello"} 525
telemt_user_octets_from_client{user="hello"} 3023595188 (2.82 GB)
telemt_user_octets_to_client{user="hello"} 86299925704 (80.37 GB)
telemt_user_unique_ips_current{user="hello"} 171
telemt_user_unique_ips_recent_window{user="hello"} 95
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 153426.3 (42h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2877529
telemt_connections_bad_total 28046
telemt_handshake_timeouts_total 193607
telemt_upstream_connect_attempt_total 34310
telemt_upstream_connect_success_total 34300
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 34310
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17774
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16396
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 125
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 3302
telemt_me_reconnect_attempts_total 28881
telemt_me_reconnect_success_total 26329
telemt_me_reader_eof_total 27923
telemt_me_idle_close_by_peer_total 27922
telemt_me_route_drop_no_conn_total 975035
telemt_me_route_drop_channel_closed_total 17
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2367151
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8335
telemt_desync_full_logged_total 2762
telemt_desync_suppressed_total 5573
telemt_desync_frames_bucket_total{bucket="1_2"} 1340
telemt_desync_frames_bucket_total{bucket="3_10"} 3039
telemt_desync_frames_bucket_total{bucket="gt_10"} 3956
telemt_pool_swap_total 145
telemt_me_writer_removed_unexpected_total 26638
telemt_me_refill_failed_total 75
telemt_me_writer_restored_same_endpoint_total 26288
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 309
telemt_user_connections_total{user="hello"} 2366534
telemt_user_connections_current{user="hello"} 1004
telemt_user_octets_from_client{user="hello"} 38620093528 (35.97 GB)
telemt_user_octets_to_client{user="hello"} 822970735013 (766.45 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 292
telemt_user_unique_ips_recent_window{user="hello"} 150
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 153426.7 (42h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1842470
telemt_connections_bad_total 18162
telemt_handshake_timeouts_total 158451
telemt_upstream_connect_attempt_total 48180
telemt_upstream_connect_success_total 45844
telemt_upstream_connect_fail_total 2199
telemt_upstream_connect_attempts_per_request{bucket="1"} 47906
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 27483
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18270
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 91
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2198
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 11892
telemt_me_reconnect_attempts_total 41327
telemt_me_reconnect_success_total 32354
telemt_me_reader_eof_total 34754
telemt_me_idle_close_by_peer_total 34747
telemt_me_route_drop_no_conn_total 658413
telemt_me_route_drop_channel_closed_total 5
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1525392
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3067
telemt_desync_full_logged_total 992
telemt_desync_suppressed_total 2075
telemt_desync_frames_bucket_total{bucket="1_2"} 828
telemt_desync_frames_bucket_total{bucket="3_10"} 1273
telemt_desync_frames_bucket_total{bucket="gt_10"} 966
telemt_pool_swap_total 133
telemt_me_writer_removed_unexpected_total 32887
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 32330
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 533
telemt_user_connections_total{user="hello"} 1530095
telemt_user_connections_current{user="hello"} 729
telemt_user_octets_from_client{user="hello"} 23611299581 (21.99 GB)
telemt_user_octets_to_client{user="hello"} 582438300558 (542.44 GB)
telemt_user_msgs_from_client{user="hello"} 44500
telemt_user_msgs_to_client{user="hello"} 116355
telemt_user_unique_ips_current{user="hello"} 204
telemt_user_unique_ips_recent_window{user="hello"} 122
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 22861.9 (6h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 371723
telemt_connections_bad_total 4139
telemt_handshake_timeouts_total 3386
telemt_upstream_connect_attempt_total 5056
telemt_upstream_connect_success_total 4908
telemt_upstream_connect_fail_total 148
telemt_upstream_connect_attempts_per_request{bucket="1"} 5056
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2290
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2613
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 148
telemt_me_keepalive_timeout_total 100
telemt_me_reconnect_attempts_total 14303
telemt_me_reconnect_success_total 3726
telemt_me_reader_eof_total 4129
telemt_me_idle_close_by_peer_total 4129
telemt_me_route_drop_no_conn_total 145754
telemt_me_route_drop_channel_closed_total 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 348004
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 3
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1174
telemt_desync_full_logged_total 366
telemt_desync_suppressed_total 808
telemt_desync_frames_bucket_total{bucket="1_2"} 394
telemt_desync_frames_bucket_total{bucket="3_10"} 469
telemt_desync_frames_bucket_total{bucket="gt_10"} 311
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 4080
telemt_me_refill_failed_total 329
telemt_me_writer_restored_same_endpoint_total 3722
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 354
telemt_user_connections_total{user="hello"} 347978
telemt_user_connections_current{user="hello"} 821
telemt_user_octets_from_client{user="hello"} 4008195732 (3.73 GB)
telemt_user_octets_to_client{user="hello"} 111820353752 (104.14 GB)
telemt_user_unique_ips_current{user="hello"} 214
telemt_user_unique_ips_recent_window{user="hello"} 118
```