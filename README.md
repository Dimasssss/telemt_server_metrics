# Server Metrics 2026-03-11 16:08:09 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 92463.3 (25h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2297225
telemt_connections_bad_total 40443
telemt_handshake_timeouts_total 53652
telemt_upstream_connect_attempt_total 19348
telemt_upstream_connect_success_total 19336
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 19348
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9729
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9513
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 93
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_keepalive_timeout_total 5007
telemt_me_reconnect_attempts_total 32530
telemt_me_reconnect_success_total 14657
telemt_me_reader_eof_total 15896
telemt_me_idle_close_by_peer_total 15896
telemt_me_route_drop_no_conn_total 852431
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2100674
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 10916
telemt_desync_full_logged_total 2972
telemt_desync_suppressed_total 7944
telemt_desync_frames_bucket_total{bucket="1_2"} 2702
telemt_desync_frames_bucket_total{bucket="3_10"} 4212
telemt_desync_frames_bucket_total{bucket="gt_10"} 4002
telemt_pool_swap_total 67
telemt_me_writer_removed_unexpected_total 15378
telemt_me_refill_failed_total 555
telemt_me_writer_restored_same_endpoint_total 14651
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 721
telemt_user_connections_total{user="hello"} 2099121
telemt_user_connections_current{user="hello"} 1361
telemt_user_octets_from_client{user="hello"} 28424057004 (26.47 GB)
telemt_user_octets_to_client{user="hello"} 592944378340 (552.22 GB)
telemt_user_unique_ips_current{user="hello"} 361
telemt_user_unique_ips_recent_window{user="hello"} 204
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 92520.2 (25h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 853157
telemt_connections_bad_total 14589
telemt_handshake_timeouts_total 61485
telemt_upstream_connect_attempt_total 29225
telemt_upstream_connect_success_total 26267
telemt_upstream_connect_fail_total 2958
telemt_upstream_connect_attempts_per_request{bucket="1"} 29225
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12246
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11773
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2039
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2958
telemt_me_keepalive_timeout_total 2635
telemt_me_reconnect_attempts_total 20774
telemt_me_reconnect_success_total 18681
telemt_me_reader_eof_total 19780
telemt_me_idle_close_by_peer_total 19777
telemt_me_route_drop_no_conn_total 332002
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 722327
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2935
telemt_desync_full_logged_total 936
telemt_desync_suppressed_total 1999
telemt_desync_frames_bucket_total{bucket="1_2"} 907
telemt_desync_frames_bucket_total{bucket="3_10"} 1054
telemt_desync_frames_bucket_total{bucket="gt_10"} 974
telemt_pool_swap_total 75
telemt_me_writer_removed_unexpected_total 18950
telemt_me_refill_failed_total 60
telemt_me_writer_restored_same_endpoint_total 18658
telemt_me_writer_restored_fallback_total 23
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 269
telemt_user_connections_total{user="hello"} 724787
telemt_user_connections_current{user="hello"} 545
telemt_user_octets_from_client{user="hello"} 8332657138 (7.76 GB)
telemt_user_octets_to_client{user="hello"} 205426284848 (191.32 GB)
telemt_user_msgs_from_client{user="hello"} 7933
telemt_user_msgs_to_client{user="hello"} 11226
telemt_user_unique_ips_current{user="hello"} 156
telemt_user_unique_ips_recent_window{user="hello"} 75
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 92520.1 (25h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1471726
telemt_connections_bad_total 8688
telemt_handshake_timeouts_total 125045
telemt_upstream_connect_attempt_total 24074
telemt_upstream_connect_success_total 23773
telemt_upstream_connect_fail_total 301
telemt_upstream_connect_attempts_per_request{bucket="1"} 24074
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12832
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10816
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 125
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 301
telemt_me_keepalive_timeout_total 1693
telemt_me_reconnect_attempts_total 40416
telemt_me_reconnect_success_total 18039
telemt_me_reader_eof_total 19545
telemt_me_idle_close_by_peer_total 19545
telemt_me_route_drop_no_conn_total 538413
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1284674
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 9
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3367
telemt_desync_full_logged_total 999
telemt_desync_suppressed_total 2368
telemt_desync_frames_bucket_total{bucket="1_2"} 832
telemt_desync_frames_bucket_total{bucket="3_10"} 1274
telemt_desync_frames_bucket_total{bucket="gt_10"} 1261
telemt_pool_swap_total 53
telemt_me_writer_removed_unexpected_total 18984
telemt_me_refill_failed_total 694
telemt_me_writer_restored_same_endpoint_total 18027
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 945
telemt_user_connections_total{user="hello"} 1284382
telemt_user_connections_current{user="hello"} 790
telemt_user_octets_from_client{user="hello"} 15443748077 (14.38 GB)
telemt_user_octets_to_client{user="hello"} 388931900785 (362.22 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 238
telemt_user_unique_ips_recent_window{user="hello"} 133
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 92520.4 (25h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1061883
telemt_connections_bad_total 77973
telemt_handshake_timeouts_total 103183
telemt_upstream_connect_attempt_total 24825
telemt_upstream_connect_success_total 24825
telemt_upstream_connect_attempts_per_request{bucket="1"} 24825
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13569
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11251
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 1063
telemt_me_reconnect_attempts_total 21294
telemt_me_reconnect_success_total 20219
telemt_me_reader_eof_total 21436
telemt_me_idle_close_by_peer_total 21435
telemt_me_seq_mismatch_total 19
telemt_me_route_drop_no_conn_total 347234
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 848790
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 30
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1758
telemt_desync_full_logged_total 677
telemt_desync_suppressed_total 1081
telemt_desync_frames_bucket_total{bucket="1_2"} 636
telemt_desync_frames_bucket_total{bucket="3_10"} 614
telemt_desync_frames_bucket_total{bucket="gt_10"} 508
telemt_pool_swap_total 80
telemt_me_writer_removed_unexpected_total 20464
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 20189
telemt_me_writer_restored_fallback_total 30
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 245
telemt_user_connections_total{user="hello"} 848108
telemt_user_connections_current{user="hello"} 620
telemt_user_octets_from_client{user="hello"} 10140775224 (9.44 GB)
telemt_user_octets_to_client{user="hello"} 250435268164 (233.24 GB)
telemt_user_unique_ips_current{user="hello"} 173
telemt_user_unique_ips_recent_window{user="hello"} 95
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 92520.2 (25h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1171290
telemt_connections_bad_total 6940
telemt_handshake_timeouts_total 11722
telemt_upstream_connect_attempt_total 25207
telemt_upstream_connect_success_total 25095
telemt_upstream_connect_fail_total 112
telemt_upstream_connect_attempts_per_request{bucket="1"} 25207
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12813
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12077
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 200
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 112
telemt_me_keepalive_timeout_total 2098
telemt_me_reconnect_attempts_total 24433
telemt_me_reconnect_success_total 20339
telemt_me_reader_eof_total 21423
telemt_me_idle_close_by_peer_total 21423
telemt_me_route_drop_no_conn_total 418147
telemt_me_route_drop_channel_closed_total 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1066361
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 4140
telemt_desync_full_logged_total 1483
telemt_desync_suppressed_total 2657
telemt_desync_frames_bucket_total{bucket="1_2"} 1376
telemt_desync_frames_bucket_total{bucket="3_10"} 1548
telemt_desync_frames_bucket_total{bucket="gt_10"} 1216
telemt_pool_swap_total 60
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 20732
telemt_me_refill_failed_total 124
telemt_me_writer_restored_same_endpoint_total 20339
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 393
telemt_user_connections_total{user="hello"} 1066065
telemt_user_connections_current{user="hello"} 746
telemt_user_octets_from_client{user="hello"} 20135504699 (18.75 GB)
telemt_user_octets_to_client{user="hello"} 371762929086 (346.23 GB)
telemt_user_msgs_from_client{user="hello"} 122
telemt_user_msgs_to_client{user="hello"} 215
telemt_user_unique_ips_current{user="hello"} 203
telemt_user_unique_ips_recent_window{user="hello"} 96
```