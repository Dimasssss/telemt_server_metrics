# Server Metrics 2026-03-13 17:48:41 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 129004.0 (35h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4116551
telemt_connections_bad_total 37527
telemt_handshake_timeouts_total 101407
telemt_upstream_connect_attempt_total 27344
telemt_upstream_connect_success_total 27165
telemt_upstream_connect_fail_total 179
telemt_upstream_connect_attempts_per_request{bucket="1"} 27344
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15029
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12015
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 121
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 179
telemt_me_keepalive_timeout_total 5689
telemt_me_reconnect_attempts_total 28479
telemt_me_reconnect_success_total 18373
telemt_me_reader_eof_total 19738
telemt_me_idle_close_by_peer_total 19737
telemt_me_route_drop_no_conn_total 1532453
telemt_me_route_drop_channel_closed_total 21
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3760005
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 14693
telemt_desync_full_logged_total 3908
telemt_desync_suppressed_total 10785
telemt_desync_frames_bucket_total{bucket="1_2"} 3644
telemt_desync_frames_bucket_total{bucket="3_10"} 5582
telemt_desync_frames_bucket_total{bucket="gt_10"} 5467
telemt_pool_swap_total 109
telemt_me_writer_removed_unexpected_total 18947
telemt_me_refill_failed_total 312
telemt_me_writer_restored_same_endpoint_total 18360
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 574
telemt_user_connections_total{user="hello"} 3762173
telemt_user_connections_current{user="hello"} 1486
telemt_user_octets_from_client{user="hello"} 52964565988 (49.33 GB)
telemt_user_octets_to_client{user="hello"} 1168009879121 (1.06 TB)
telemt_user_msgs_from_client{user="hello"} 5023
telemt_user_msgs_to_client{user="hello"} 14147
telemt_user_unique_ips_current{user="hello"} 432
telemt_user_unique_ips_recent_window{user="hello"} 201
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 28667.8 (7h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 428323
telemt_connections_bad_total 32469
telemt_handshake_timeouts_total 10460
telemt_upstream_connect_attempt_total 8180
telemt_upstream_connect_success_total 8006
telemt_upstream_connect_fail_total 174
telemt_upstream_connect_attempts_per_request{bucket="1"} 8180
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4613
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3254
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 19
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 120
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 174
telemt_me_keepalive_timeout_total 1601
telemt_me_reconnect_attempts_total 8532
telemt_me_reconnect_success_total 5135
telemt_me_reader_eof_total 5433
telemt_me_idle_close_by_peer_total 5432
telemt_me_route_drop_no_conn_total 160984
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 373106
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1281
telemt_desync_full_logged_total 330
telemt_desync_suppressed_total 951
telemt_desync_frames_bucket_total{bucket="1_2"} 248
telemt_desync_frames_bucket_total{bucket="3_10"} 601
telemt_desync_frames_bucket_total{bucket="gt_10"} 432
telemt_pool_swap_total 21
telemt_me_writer_removed_unexpected_total 5308
telemt_me_refill_failed_total 102
telemt_me_writer_restored_same_endpoint_total 5127
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 600
telemt_me_writer_removed_unexpected_minus_restored_total 173
telemt_user_connections_total{user="hello"} 374442
telemt_user_connections_current{user="hello"} 592
telemt_user_octets_from_client{user="hello"} 3837021891 (3.57 GB)
telemt_user_octets_to_client{user="hello"} 115255041412 (107.34 GB)
telemt_user_msgs_from_client{user="hello"} 4402
telemt_user_msgs_to_client{user="hello"} 9145
telemt_user_unique_ips_current{user="hello"} 175
telemt_user_unique_ips_recent_window{user="hello"} 103
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 158624.5 (44h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3011490
telemt_connections_bad_total 28751
telemt_handshake_timeouts_total 201480
telemt_upstream_connect_attempt_total 35434
telemt_upstream_connect_success_total 35424
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 35434
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18318
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16971
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 130
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 3442
telemt_me_reconnect_attempts_total 29737
telemt_me_reconnect_success_total 27183
telemt_me_reader_eof_total 28824
telemt_me_idle_close_by_peer_total 28823
telemt_me_route_drop_no_conn_total 1026898
telemt_me_route_drop_channel_closed_total 18
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2488648
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8520
telemt_desync_full_logged_total 2825
telemt_desync_suppressed_total 5695
telemt_desync_frames_bucket_total{bucket="1_2"} 1375
telemt_desync_frames_bucket_total{bucket="3_10"} 3118
telemt_desync_frames_bucket_total{bucket="gt_10"} 4027
telemt_pool_swap_total 149
telemt_me_writer_removed_unexpected_total 27499
telemt_me_refill_failed_total 75
telemt_me_writer_restored_same_endpoint_total 27142
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 316
telemt_user_connections_total{user="hello"} 2487986
telemt_user_connections_current{user="hello"} 1130
telemt_user_octets_from_client{user="hello"} 40838345540 (38.03 GB)
telemt_user_octets_to_client{user="hello"} 867329787009 (807.76 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 306
telemt_user_unique_ips_recent_window{user="hello"} 165
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 158625.0 (44h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1939284
telemt_connections_bad_total 18257
telemt_handshake_timeouts_total 178801
telemt_upstream_connect_attempt_total 49289
telemt_upstream_connect_success_total 46948
telemt_upstream_connect_fail_total 2204
telemt_upstream_connect_attempts_per_request{bucket="1"} 49015
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 28064
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18793
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 91
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2203
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 11970
telemt_me_reconnect_attempts_total 42168
telemt_me_reconnect_success_total 33185
telemt_me_reader_eof_total 35639
telemt_me_idle_close_by_peer_total 35632
telemt_me_route_drop_no_conn_total 689040
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1599782
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3140
telemt_desync_full_logged_total 1022
telemt_desync_suppressed_total 2118
telemt_desync_frames_bucket_total{bucket="1_2"} 873
telemt_desync_frames_bucket_total{bucket="3_10"} 1288
telemt_desync_frames_bucket_total{bucket="gt_10"} 979
telemt_pool_swap_total 138
telemt_me_writer_removed_unexpected_total 33732
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 33161
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 547
telemt_user_connections_total{user="hello"} 1604478
telemt_user_connections_current{user="hello"} 702
telemt_user_octets_from_client{user="hello"} 24674997153 (22.98 GB)
telemt_user_octets_to_client{user="hello"} 606709433922 (565.04 GB)
telemt_user_msgs_from_client{user="hello"} 44500
telemt_user_msgs_to_client{user="hello"} 116355
telemt_user_unique_ips_current{user="hello"} 191
telemt_user_unique_ips_recent_window{user="hello"} 106
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 28060.5 (7h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 459257
telemt_connections_bad_total 4627
telemt_handshake_timeouts_total 4831
telemt_upstream_connect_attempt_total 6443
telemt_upstream_connect_success_total 6234
telemt_upstream_connect_fail_total 209
telemt_upstream_connect_attempts_per_request{bucket="1"} 6443
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2909
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3316
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 209
telemt_me_keepalive_timeout_total 869
telemt_me_reconnect_attempts_total 18420
telemt_me_reconnect_success_total 4788
telemt_me_reader_eof_total 5307
telemt_me_idle_close_by_peer_total 5307
telemt_me_route_drop_no_conn_total 175944
telemt_me_route_drop_channel_closed_total 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 429319
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 3
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1290
telemt_desync_full_logged_total 414
telemt_desync_suppressed_total 876
telemt_desync_frames_bucket_total{bucket="1_2"} 419
telemt_desync_frames_bucket_total{bucket="3_10"} 513
telemt_desync_frames_bucket_total{bucket="gt_10"} 358
telemt_pool_swap_total 8
telemt_me_writer_removed_unexpected_total 5251
telemt_me_refill_failed_total 424
telemt_me_writer_restored_same_endpoint_total 4784
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 463
telemt_user_connections_total{user="hello"} 429291
telemt_user_connections_current{user="hello"} 784
telemt_user_octets_from_client{user="hello"} 4873721004 (4.54 GB)
telemt_user_octets_to_client{user="hello"} 134467972152 (125.23 GB)
telemt_user_unique_ips_current{user="hello"} 191
telemt_user_unique_ips_recent_window{user="hello"} 95
```