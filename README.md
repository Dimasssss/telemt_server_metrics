# Server Metrics 2026-03-13 16:37:19 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 124722.0 (34h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3944510
telemt_connections_bad_total 37508
telemt_handshake_timeouts_total 93563
telemt_upstream_connect_attempt_total 24184
telemt_upstream_connect_success_total 24046
telemt_upstream_connect_fail_total 138
telemt_upstream_connect_attempts_per_request{bucket="1"} 24184
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12412
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11570
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 64
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 138
telemt_me_keepalive_timeout_total 2241
telemt_me_reconnect_attempts_total 27943
telemt_me_reconnect_success_total 17849
telemt_me_reader_eof_total 19174
telemt_me_idle_close_by_peer_total 19173
telemt_me_route_drop_no_conn_total 1464280
telemt_me_route_drop_channel_closed_total 19
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3606968
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 14281
telemt_desync_full_logged_total 3770
telemt_desync_suppressed_total 10511
telemt_desync_frames_bucket_total{bucket="1_2"} 3572
telemt_desync_frames_bucket_total{bucket="3_10"} 5407
telemt_desync_frames_bucket_total{bucket="gt_10"} 5302
telemt_pool_swap_total 104
telemt_me_writer_removed_unexpected_total 18408
telemt_me_refill_failed_total 312
telemt_me_writer_restored_same_endpoint_total 17836
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 559
telemt_user_connections_total{user="hello"} 3606772
telemt_user_connections_current{user="hello"} 1777
telemt_user_octets_from_client{user="hello"} 50794197056 (47.31 GB)
telemt_user_octets_to_client{user="hello"} 1126000554816 (1.02 TB)
telemt_user_unique_ips_current{user="hello"} 475
telemt_user_unique_ips_recent_window{user="hello"} 236
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 24385.9 (6h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 358719
telemt_connections_bad_total 24501
telemt_handshake_timeouts_total 10000
telemt_upstream_connect_attempt_total 5784
telemt_upstream_connect_success_total 5696
telemt_upstream_connect_fail_total 88
telemt_upstream_connect_attempts_per_request{bucket="1"} 5784
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2920
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2715
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 17
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 44
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 88
telemt_me_keepalive_timeout_total 132
telemt_me_reconnect_attempts_total 6718
telemt_me_reconnect_success_total 4421
telemt_me_reader_eof_total 4671
telemt_me_idle_close_by_peer_total 4670
telemt_me_route_drop_no_conn_total 129647
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 315328
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1127
telemt_desync_full_logged_total 292
telemt_desync_suppressed_total 835
telemt_desync_frames_bucket_total{bucket="1_2"} 219
telemt_desync_frames_bucket_total{bucket="3_10"} 545
telemt_desync_frames_bucket_total{bucket="gt_10"} 363
telemt_pool_swap_total 18
telemt_me_writer_removed_unexpected_total 4553
telemt_me_refill_failed_total 69
telemt_me_writer_restored_same_endpoint_total 4414
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 132
telemt_user_connections_total{user="hello"} 315359
telemt_user_connections_current{user="hello"} 596
telemt_user_octets_from_client{user="hello"} 3138557744 (2.92 GB)
telemt_user_octets_to_client{user="hello"} 90191764896 (84.00 GB)
telemt_user_unique_ips_current{user="hello"} 184
telemt_user_unique_ips_recent_window{user="hello"} 117
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 154342.7 (42h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2901553
telemt_connections_bad_total 28097
telemt_handshake_timeouts_total 195302
telemt_upstream_connect_attempt_total 34510
telemt_upstream_connect_success_total 34500
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 34510
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17862
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16507
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 126
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 3315
telemt_me_reconnect_attempts_total 29034
telemt_me_reconnect_success_total 26481
telemt_me_reader_eof_total 28078
telemt_me_idle_close_by_peer_total 28077
telemt_me_route_drop_no_conn_total 984305
telemt_me_route_drop_channel_closed_total 18
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2388907
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8388
telemt_desync_full_logged_total 2772
telemt_desync_suppressed_total 5616
telemt_desync_frames_bucket_total{bucket="1_2"} 1352
telemt_desync_frames_bucket_total{bucket="3_10"} 3063
telemt_desync_frames_bucket_total{bucket="gt_10"} 3973
telemt_pool_swap_total 145
telemt_me_writer_removed_unexpected_total 26793
telemt_me_refill_failed_total 75
telemt_me_writer_restored_same_endpoint_total 26440
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 312
telemt_user_connections_total{user="hello"} 2388275
telemt_user_connections_current{user="hello"} 1054
telemt_user_octets_from_client{user="hello"} 39032699348 (36.35 GB)
telemt_user_octets_to_client{user="hello"} 830357279465 (773.33 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 296
telemt_user_unique_ips_recent_window{user="hello"} 153
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 154343.2 (42h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1865060
telemt_connections_bad_total 18166
telemt_handshake_timeouts_total 166700
telemt_upstream_connect_attempt_total 48374
telemt_upstream_connect_success_total 46037
telemt_upstream_connect_fail_total 2199
telemt_upstream_connect_attempts_per_request{bucket="1"} 48099
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 27597
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18349
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 91
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2198
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 11909
telemt_me_reconnect_attempts_total 41477
telemt_me_reconnect_success_total 32502
telemt_me_reader_eof_total 34914
telemt_me_idle_close_by_peer_total 34907
telemt_me_route_drop_no_conn_total 663030
telemt_me_route_drop_channel_closed_total 5
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1539434
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3077
telemt_desync_full_logged_total 998
telemt_desync_suppressed_total 2079
telemt_desync_frames_bucket_total{bucket="1_2"} 837
telemt_desync_frames_bucket_total{bucket="3_10"} 1274
telemt_desync_frames_bucket_total{bucket="gt_10"} 966
telemt_pool_swap_total 134
telemt_me_writer_removed_unexpected_total 33039
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 32478
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 537
telemt_user_connections_total{user="hello"} 1544133
telemt_user_connections_current{user="hello"} 745
telemt_user_octets_from_client{user="hello"} 23871429357 (22.23 GB)
telemt_user_octets_to_client{user="hello"} 586133802602 (545.88 GB)
telemt_user_msgs_from_client{user="hello"} 44500
telemt_user_msgs_to_client{user="hello"} 116355
telemt_user_unique_ips_current{user="hello"} 202
telemt_user_unique_ips_recent_window{user="hello"} 103
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 23778.7 (6h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 386621
telemt_connections_bad_total 4174
telemt_handshake_timeouts_total 3556
telemt_upstream_connect_attempt_total 5360
telemt_upstream_connect_success_total 5201
telemt_upstream_connect_fail_total 159
telemt_upstream_connect_attempts_per_request{bucket="1"} 5360
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2404
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2792
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 159
telemt_me_keepalive_timeout_total 105
telemt_me_reconnect_attempts_total 15672
telemt_me_reconnect_success_total 3975
telemt_me_reader_eof_total 4416
telemt_me_idle_close_by_peer_total 4416
telemt_me_route_drop_no_conn_total 151114
telemt_me_route_drop_channel_closed_total 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 361150
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 3
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1205
telemt_desync_full_logged_total 376
telemt_desync_suppressed_total 829
telemt_desync_frames_bucket_total{bucket="1_2"} 405
telemt_desync_frames_bucket_total{bucket="3_10"} 479
telemt_desync_frames_bucket_total{bucket="gt_10"} 321
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 4367
telemt_me_refill_failed_total 364
telemt_me_writer_restored_same_endpoint_total 3971
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 392
telemt_user_connections_total{user="hello"} 361125
telemt_user_connections_current{user="hello"} 719
telemt_user_octets_from_client{user="hello"} 4159591692 (3.87 GB)
telemt_user_octets_to_client{user="hello"} 116032979356 (108.06 GB)
telemt_user_unique_ips_current{user="hello"} 189
telemt_user_unique_ips_recent_window{user="hello"} 103
```