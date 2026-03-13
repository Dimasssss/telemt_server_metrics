# Server Metrics 2026-03-13 14:49:56 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 118278.8 (32h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3648907
telemt_connections_bad_total 37406
telemt_handshake_timeouts_total 73019
telemt_upstream_connect_attempt_total 23089
telemt_upstream_connect_success_total 22959
telemt_upstream_connect_fail_total 130
telemt_upstream_connect_attempts_per_request{bucket="1"} 23089
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11843
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11057
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 59
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 130
telemt_me_keepalive_timeout_total 2166
telemt_me_reconnect_attempts_total 27159
telemt_me_reconnect_success_total 17072
telemt_me_reader_eof_total 18352
telemt_me_idle_close_by_peer_total 18351
telemt_me_route_drop_no_conn_total 1351603
telemt_me_route_drop_channel_closed_total 17
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3341883
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 13734
telemt_desync_full_logged_total 3610
telemt_desync_suppressed_total 10124
telemt_desync_frames_bucket_total{bucket="1_2"} 3473
telemt_desync_frames_bucket_total{bucket="3_10"} 5201
telemt_desync_frames_bucket_total{bucket="gt_10"} 5060
telemt_pool_swap_total 98
telemt_me_writer_removed_unexpected_total 17624
telemt_me_refill_failed_total 312
telemt_me_writer_restored_same_endpoint_total 17059
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 552
telemt_user_connections_total{user="hello"} 3341601
telemt_user_connections_current{user="hello"} 1674
telemt_user_octets_from_client{user="hello"} 45795770280 (42.65 GB)
telemt_user_octets_to_client{user="hello"} 1056779170952 (984.20 GB)
telemt_user_unique_ips_current{user="hello"} 464
telemt_user_unique_ips_recent_window{user="hello"} 263
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 17942.4 (4h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 253939
telemt_connections_bad_total 14449
telemt_handshake_timeouts_total 6216
telemt_upstream_connect_attempt_total 4334
telemt_upstream_connect_success_total 4254
telemt_upstream_connect_fail_total 80
telemt_upstream_connect_attempts_per_request{bucket="1"} 4334
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2179
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2028
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 12
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 35
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 80
telemt_me_keepalive_timeout_total 81
telemt_me_reconnect_attempts_total 5616
telemt_me_reconnect_success_total 3326
telemt_me_reader_eof_total 3525
telemt_me_idle_close_by_peer_total 3525
telemt_me_route_drop_no_conn_total 91800
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 226601
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 891
telemt_desync_full_logged_total 221
telemt_desync_suppressed_total 670
telemt_desync_frames_bucket_total{bucket="1_2"} 164
telemt_desync_frames_bucket_total{bucket="3_10"} 439
telemt_desync_frames_bucket_total{bucket="gt_10"} 288
telemt_pool_swap_total 13
telemt_me_writer_removed_unexpected_total 3434
telemt_me_refill_failed_total 69
telemt_me_writer_restored_same_endpoint_total 3319
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 108
telemt_user_connections_total{user="hello"} 226629
telemt_user_connections_current{user="hello"} 545
telemt_user_octets_from_client{user="hello"} 2333132548 (2.17 GB)
telemt_user_octets_to_client{user="hello"} 64532649392 (60.10 GB)
telemt_user_unique_ips_current{user="hello"} 174
telemt_user_unique_ips_recent_window{user="hello"} 90
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 147899.2 (41h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2710656
telemt_connections_bad_total 27398
telemt_handshake_timeouts_total 180008
telemt_upstream_connect_attempt_total 33313
telemt_upstream_connect_success_total 33303
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 33313
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17294
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15882
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 122
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 3245
telemt_me_reconnect_attempts_total 28144
telemt_me_reconnect_success_total 25597
telemt_me_reader_eof_total 27144
telemt_me_idle_close_by_peer_total 27143
telemt_me_route_drop_no_conn_total 913580
telemt_me_route_drop_channel_closed_total 16
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2219556
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7984
telemt_desync_full_logged_total 2613
telemt_desync_suppressed_total 5371
telemt_desync_frames_bucket_total{bucket="1_2"} 1262
telemt_desync_frames_bucket_total{bucket="3_10"} 2911
telemt_desync_frames_bucket_total{bucket="gt_10"} 3811
telemt_pool_swap_total 139
telemt_me_writer_removed_unexpected_total 25895
telemt_me_refill_failed_total 75
telemt_me_writer_restored_same_endpoint_total 25556
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 298
telemt_user_connections_total{user="hello"} 2218934
telemt_user_connections_current{user="hello"} 970
telemt_user_octets_from_client{user="hello"} 36793877168 (34.27 GB)
telemt_user_octets_to_client{user="hello"} 784991924385 (731.08 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 291
telemt_user_unique_ips_recent_window{user="hello"} 166
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 147899.6 (41h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1727826
telemt_connections_bad_total 18125
telemt_handshake_timeouts_total 127525
telemt_upstream_connect_attempt_total 46747
telemt_upstream_connect_success_total 44419
telemt_upstream_connect_fail_total 2191
telemt_upstream_connect_attempts_per_request{bucket="1"} 46473
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26737
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17591
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 91
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2190
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 11849
telemt_me_reconnect_attempts_total 40165
telemt_me_reconnect_success_total 31196
telemt_me_reader_eof_total 33539
telemt_me_idle_close_by_peer_total 33532
telemt_me_route_drop_no_conn_total 618060
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1443844
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2917
telemt_desync_full_logged_total 941
telemt_desync_suppressed_total 1976
telemt_desync_frames_bucket_total{bucket="1_2"} 776
telemt_desync_frames_bucket_total{bucket="3_10"} 1216
telemt_desync_frames_bucket_total{bucket="gt_10"} 925
telemt_pool_swap_total 130
telemt_me_writer_removed_unexpected_total 31711
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 31172
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 515
telemt_user_connections_total{user="hello"} 1448559
telemt_user_connections_current{user="hello"} 645
telemt_user_octets_from_client{user="hello"} 22667225001 (21.11 GB)
telemt_user_octets_to_client{user="hello"} 555929880930 (517.75 GB)
telemt_user_msgs_from_client{user="hello"} 44500
telemt_user_msgs_to_client{user="hello"} 116355
telemt_user_unique_ips_current{user="hello"} 199
telemt_user_unique_ips_recent_window{user="hello"} 107
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 17335.2 (4h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 275039
telemt_connections_bad_total 3922
telemt_handshake_timeouts_total 2662
telemt_upstream_connect_attempt_total 3734
telemt_upstream_connect_success_total 3615
telemt_upstream_connect_fail_total 119
telemt_upstream_connect_attempts_per_request{bucket="1"} 3734
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1728
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1883
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 119
telemt_me_keepalive_timeout_total 69
telemt_me_reconnect_attempts_total 11960
telemt_me_reconnect_success_total 2698
telemt_me_reader_eof_total 3019
telemt_me_idle_close_by_peer_total 3019
telemt_me_route_drop_no_conn_total 107946
telemt_me_route_drop_channel_closed_total 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 256758
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 3
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 805
telemt_desync_full_logged_total 261
telemt_desync_suppressed_total 544
telemt_desync_frames_bucket_total{bucket="1_2"} 300
telemt_desync_frames_bucket_total{bucket="3_10"} 314
telemt_desync_frames_bucket_total{bucket="gt_10"} 191
telemt_pool_swap_total 5
telemt_me_writer_removed_unexpected_total 2996
telemt_me_refill_failed_total 288
telemt_me_writer_restored_same_endpoint_total 2694
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 298
telemt_user_connections_total{user="hello"} 256738
telemt_user_connections_current{user="hello"} 855
telemt_user_octets_from_client{user="hello"} 2980713864 (2.78 GB)
telemt_user_octets_to_client{user="hello"} 84268223904 (78.48 GB)
telemt_user_unique_ips_current{user="hello"} 207
telemt_user_unique_ips_recent_window{user="hello"} 115
```