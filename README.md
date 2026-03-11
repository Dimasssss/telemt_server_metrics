# Server Metrics 2026-03-11 14:31:05 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 86639.4 (24h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2090058
telemt_connections_bad_total 31805
telemt_handshake_timeouts_total 52106
telemt_upstream_connect_attempt_total 18323
telemt_upstream_connect_success_total 18311
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 18323
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9247
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8974
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 89
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_keepalive_timeout_total 4849
telemt_me_reconnect_attempts_total 29152
telemt_me_reconnect_success_total 13910
telemt_me_reader_eof_total 15036
telemt_me_idle_close_by_peer_total 15036
telemt_me_route_drop_no_conn_total 771779
telemt_me_route_drop_channel_closed_total 7
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1911361
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 10046
telemt_desync_full_logged_total 2723
telemt_desync_suppressed_total 7323
telemt_desync_frames_bucket_total{bucket="1_2"} 2496
telemt_desync_frames_bucket_total{bucket="3_10"} 3874
telemt_desync_frames_bucket_total{bucket="gt_10"} 3676
telemt_pool_swap_total 64
telemt_me_writer_removed_unexpected_total 14535
telemt_me_refill_failed_total 473
telemt_me_writer_restored_same_endpoint_total 13904
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 625
telemt_user_connections_total{user="hello"} 1909869
telemt_user_connections_current{user="hello"} 1412
telemt_user_octets_from_client{user="hello"} 25686793768 (23.92 GB)
telemt_user_octets_to_client{user="hello"} 543300615844 (505.99 GB)
telemt_user_unique_ips_current{user="hello"} 380
telemt_user_unique_ips_recent_window{user="hello"} 211
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 86696.2 (24h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 783559
telemt_connections_bad_total 13167
telemt_handshake_timeouts_total 52906
telemt_upstream_connect_attempt_total 27737
telemt_upstream_connect_success_total 24788
telemt_upstream_connect_fail_total 2949
telemt_upstream_connect_attempts_per_request{bucket="1"} 27737
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11470
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11070
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2039
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2949
telemt_me_keepalive_timeout_total 2523
telemt_me_reconnect_attempts_total 19566
telemt_me_reconnect_success_total 17478
telemt_me_reader_eof_total 18513
telemt_me_idle_close_by_peer_total 18510
telemt_me_route_drop_no_conn_total 306693
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 664065
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2834
telemt_desync_full_logged_total 898
telemt_desync_suppressed_total 1936
telemt_desync_frames_bucket_total{bucket="1_2"} 881
telemt_desync_frames_bucket_total{bucket="3_10"} 1029
telemt_desync_frames_bucket_total{bucket="gt_10"} 924
telemt_pool_swap_total 71
telemt_me_writer_removed_unexpected_total 17735
telemt_me_refill_failed_total 60
telemt_me_writer_restored_same_endpoint_total 17455
telemt_me_writer_restored_fallback_total 23
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 257
telemt_user_connections_total{user="hello"} 666542
telemt_user_connections_current{user="hello"} 609
telemt_user_octets_from_client{user="hello"} 7061715802 (6.58 GB)
telemt_user_octets_to_client{user="hello"} 188506937132 (175.56 GB)
telemt_user_msgs_from_client{user="hello"} 7933
telemt_user_msgs_to_client{user="hello"} 11226
telemt_user_unique_ips_current{user="hello"} 163
telemt_user_unique_ips_recent_window{user="hello"} 104
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 86696.0 (24h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1356498
telemt_connections_bad_total 8455
telemt_handshake_timeouts_total 122054
telemt_upstream_connect_attempt_total 23055
telemt_upstream_connect_success_total 22781
telemt_upstream_connect_fail_total 274
telemt_upstream_connect_attempts_per_request{bucket="1"} 23055
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12306
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10361
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 114
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 274
telemt_me_keepalive_timeout_total 1485
telemt_me_reconnect_attempts_total 33437
telemt_me_reconnect_success_total 17326
telemt_me_reader_eof_total 18622
telemt_me_idle_close_by_peer_total 18622
telemt_me_route_drop_no_conn_total 490507
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1175246
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3140
telemt_desync_full_logged_total 925
telemt_desync_suppressed_total 2215
telemt_desync_frames_bucket_total{bucket="1_2"} 762
telemt_desync_frames_bucket_total{bucket="3_10"} 1190
telemt_desync_frames_bucket_total{bucket="gt_10"} 1188
telemt_pool_swap_total 53
telemt_me_writer_removed_unexpected_total 18063
telemt_me_refill_failed_total 499
telemt_me_writer_restored_same_endpoint_total 17315
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 737
telemt_user_connections_total{user="hello"} 1175042
telemt_user_connections_current{user="hello"} 901
telemt_user_octets_from_client{user="hello"} 14131372065 (13.16 GB)
telemt_user_octets_to_client{user="hello"} 350575560149 (326.50 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 260
telemt_user_unique_ips_recent_window{user="hello"} 164
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 86696.6 (24h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 975416
telemt_connections_bad_total 77524
telemt_handshake_timeouts_total 93486
telemt_upstream_connect_attempt_total 23430
telemt_upstream_connect_success_total 23430
telemt_upstream_connect_attempts_per_request{bucket="1"} 23430
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12823
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10602
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 953
telemt_me_reconnect_attempts_total 20161
telemt_me_reconnect_success_total 19088
telemt_me_reader_eof_total 20246
telemt_me_idle_close_by_peer_total 20245
telemt_me_seq_mismatch_total 17
telemt_me_route_drop_no_conn_total 316960
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 777870
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 28
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1642
telemt_desync_full_logged_total 640
telemt_desync_suppressed_total 1002
telemt_desync_frames_bucket_total{bucket="1_2"} 592
telemt_desync_frames_bucket_total{bucket="3_10"} 575
telemt_desync_frames_bucket_total{bucket="gt_10"} 475
telemt_pool_swap_total 76
telemt_me_writer_removed_unexpected_total 19324
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 19060
telemt_me_writer_restored_fallback_total 28
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 236
telemt_user_connections_total{user="hello"} 777203
telemt_user_connections_current{user="hello"} 627
telemt_user_octets_from_client{user="hello"} 9115618120 (8.49 GB)
telemt_user_octets_to_client{user="hello"} 226728166780 (211.16 GB)
telemt_user_unique_ips_current{user="hello"} 170
telemt_user_unique_ips_recent_window{user="hello"} 107
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 86696.1 (24h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1071100
telemt_connections_bad_total 6936
telemt_handshake_timeouts_total 10542
telemt_upstream_connect_attempt_total 23503
telemt_upstream_connect_success_total 23398
telemt_upstream_connect_fail_total 105
telemt_upstream_connect_attempts_per_request{bucket="1"} 23503
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11971
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11234
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 188
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 105
telemt_me_keepalive_timeout_total 1694
telemt_me_reconnect_attempts_total 23005
telemt_me_reconnect_success_total 18922
telemt_me_reader_eof_total 19951
telemt_me_idle_close_by_peer_total 19951
telemt_me_route_drop_no_conn_total 379890
telemt_me_route_drop_channel_closed_total 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 972837
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 3798
telemt_desync_full_logged_total 1398
telemt_desync_suppressed_total 2400
telemt_desync_frames_bucket_total{bucket="1_2"} 1329
telemt_desync_frames_bucket_total{bucket="3_10"} 1432
telemt_desync_frames_bucket_total{bucket="gt_10"} 1037
telemt_pool_swap_total 58
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 19293
telemt_me_refill_failed_total 124
telemt_me_writer_restored_same_endpoint_total 18922
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 371
telemt_user_connections_total{user="hello"} 972569
telemt_user_connections_current{user="hello"} 760
telemt_user_octets_from_client{user="hello"} 14001346867 (13.04 GB)
telemt_user_octets_to_client{user="hello"} 341988702062 (318.50 GB)
telemt_user_msgs_from_client{user="hello"} 122
telemt_user_msgs_to_client{user="hello"} 215
telemt_user_unique_ips_current{user="hello"} 204
telemt_user_unique_ips_recent_window{user="hello"} 124
```