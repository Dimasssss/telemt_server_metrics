# Server Metrics 2026-03-15 09:34:06 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.18

telemt_uptime_seconds 40776.8 (11h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 908109
telemt_connections_bad_total 46474
telemt_handshake_timeouts_total 6649
telemt_upstream_connect_attempt_total 8225
telemt_upstream_connect_success_total 8190
telemt_upstream_connect_fail_total 35
telemt_upstream_connect_attempts_per_request{bucket="1"} 8225
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4294
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3879
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 17
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 35
telemt_me_keepalive_timeout_total 8
telemt_me_reconnect_attempts_total 6175
telemt_me_reconnect_success_total 6141
telemt_me_reader_eof_total 6500
telemt_me_idle_close_by_peer_total 6500
telemt_me_route_drop_no_conn_total 299512
telemt_me_route_drop_channel_closed_total 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 767533
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2625
telemt_desync_full_logged_total 787
telemt_desync_suppressed_total 1838
telemt_desync_frames_bucket_total{bucket="1_2"} 614
telemt_desync_frames_bucket_total{bucket="3_10"} 996
telemt_desync_frames_bucket_total{bucket="gt_10"} 1015
telemt_pool_swap_total 37
telemt_me_writer_removed_unexpected_total 6227
telemt_me_writer_restored_same_endpoint_total 6130
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 296
telemt_me_writer_removed_unexpected_minus_restored_total 86
telemt_user_connections_total{user="hello"} 767514
telemt_user_connections_current{user="hello"} 1960
telemt_user_octets_from_client{user="hello"} 11136943824 (10.37 GB)
telemt_user_octets_to_client{user="hello"} 297235583260 (276.82 GB)
telemt_user_unique_ips_current{user="hello"} 548
telemt_user_unique_ips_recent_window{user="hello"} 233
```

## server2

```
telemt 3.3.18

telemt_uptime_seconds 40777.8 (11h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 359763
telemt_connections_bad_total 19800
telemt_handshake_timeouts_total 13908
telemt_upstream_connect_attempt_total 10835
telemt_upstream_connect_success_total 10779
telemt_upstream_connect_fail_total 56
telemt_upstream_connect_attempts_per_request{bucket="1"} 10835
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5854
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4833
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 27
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 65
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 56
telemt_me_keepalive_timeout_total 15
telemt_me_reconnect_attempts_total 8457
telemt_me_reconnect_success_total 8404
telemt_me_reader_eof_total 8905
telemt_me_idle_close_by_peer_total 8905
telemt_me_route_drop_no_conn_total 91471
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 284833
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 16
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1029
telemt_desync_full_logged_total 352
telemt_desync_suppressed_total 677
telemt_desync_frames_bucket_total{bucket="1_2"} 330
telemt_desync_frames_bucket_total{bucket="3_10"} 381
telemt_desync_frames_bucket_total{bucket="gt_10"} 318
telemt_pool_swap_total 39
telemt_me_writer_removed_unexpected_total 8478
telemt_me_writer_restored_same_endpoint_total 8396
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 61
telemt_me_writer_removed_unexpected_minus_restored_total 74
telemt_user_connections_total{user="hello"} 285116
telemt_user_connections_current{user="hello"} 725
telemt_user_octets_from_client{user="hello"} 4194881767 (3.91 GB)
telemt_user_octets_to_client{user="hello"} 106890241848 (99.55 GB)
telemt_user_msgs_from_client{user="hello"} 620
telemt_user_msgs_to_client{user="hello"} 1332
telemt_user_unique_ips_current{user="hello"} 230
telemt_user_unique_ips_recent_window{user="hello"} 115
```

## server3

```
telemt 3.3.18

telemt_uptime_seconds 40777.8 (11h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 644678
telemt_connections_bad_total 21534
telemt_handshake_timeouts_total 65596
telemt_upstream_connect_attempt_total 9151
telemt_upstream_connect_success_total 9112
telemt_upstream_connect_fail_total 39
telemt_upstream_connect_attempts_per_request{bucket="1"} 9151
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4769
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4292
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 51
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 39
telemt_me_reconnect_attempts_total 7093
telemt_me_reconnect_success_total 7047
telemt_me_reader_eof_total 7459
telemt_me_idle_close_by_peer_total 7459
telemt_me_route_drop_no_conn_total 187634
telemt_me_route_drop_channel_closed_total 15
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 499030
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1002
telemt_desync_full_logged_total 384
telemt_desync_suppressed_total 618
telemt_desync_frames_bucket_total{bucket="1_2"} 214
telemt_desync_frames_bucket_total{bucket="3_10"} 365
telemt_desync_frames_bucket_total{bucket="gt_10"} 423
telemt_pool_swap_total 40
telemt_me_writer_removed_unexpected_total 7133
telemt_me_writer_restored_same_endpoint_total 7028
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 242
telemt_me_writer_removed_unexpected_minus_restored_total 86
telemt_user_connections_total{user="hello"} 498547
telemt_user_connections_current{user="hello"} 1150
telemt_user_octets_from_client{user="hello"} 7571102996 (7.05 GB)
telemt_user_octets_to_client{user="hello"} 199711326860 (186.00 GB)
telemt_user_unique_ips_current{user="hello"} 335
telemt_user_unique_ips_recent_window{user="hello"} 176
```

## server4

```
telemt 3.3.18

telemt_uptime_seconds 40777.7 (11h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 381036
telemt_connections_bad_total 52701
telemt_handshake_timeouts_total 24155
telemt_upstream_connect_attempt_total 12773
telemt_upstream_connect_success_total 12463
telemt_upstream_connect_fail_total 310
telemt_upstream_connect_attempts_per_request{bucket="1"} 12773
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5831
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6629
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 310
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 28109
telemt_me_reconnect_success_total 10407
telemt_me_reader_eof_total 11271
telemt_me_idle_close_by_peer_total 11271
telemt_me_seq_mismatch_total 16
telemt_me_route_drop_no_conn_total 102264
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 284631
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 33
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 706
telemt_desync_full_logged_total 172
telemt_desync_suppressed_total 534
telemt_desync_frames_bucket_total{bucket="1_2"} 167
telemt_desync_frames_bucket_total{bucket="3_10"} 295
telemt_desync_frames_bucket_total{bucket="gt_10"} 244
telemt_pool_swap_total 16
telemt_me_writer_removed_unexpected_total 11050
telemt_me_refill_failed_total 553
telemt_me_writer_restored_same_endpoint_total 10377
telemt_me_writer_restored_fallback_total 30
telemt_me_async_recovery_trigger_total 96
telemt_me_writer_removed_unexpected_minus_restored_total 643
telemt_user_connections_total{user="hello"} 284641
telemt_user_connections_current{user="hello"} 613
telemt_user_octets_from_client{user="hello"} 3249504900 (3.03 GB)
telemt_user_octets_to_client{user="hello"} 91727144432 (85.43 GB)
telemt_user_unique_ips_current{user="hello"} 205
telemt_user_unique_ips_recent_window{user="hello"} 101
```

## server5

```
telemt 3.3.18

telemt_uptime_seconds 40778.4 (11h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 356923
telemt_connections_bad_total 3838
telemt_handshake_timeouts_total 4102
telemt_upstream_connect_attempt_total 9117
telemt_upstream_connect_success_total 9076
telemt_upstream_connect_fail_total 41
telemt_upstream_connect_attempts_per_request{bucket="1"} 9117
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4129
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4942
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 41
telemt_me_reconnect_attempts_total 7058
telemt_me_reconnect_success_total 7024
telemt_me_reader_eof_total 7474
telemt_me_idle_close_by_peer_total 7474
telemt_me_route_drop_no_conn_total 97081
telemt_me_route_drop_channel_closed_total 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 302472
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1206
telemt_desync_full_logged_total 387
telemt_desync_suppressed_total 819
telemt_desync_frames_bucket_total{bucket="1_2"} 359
telemt_desync_frames_bucket_total{bucket="3_10"} 493
telemt_desync_frames_bucket_total{bucket="gt_10"} 354
telemt_pool_swap_total 40
telemt_me_writer_removed_unexpected_total 7096
telemt_me_writer_restored_same_endpoint_total 7016
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 54
telemt_me_writer_removed_unexpected_minus_restored_total 72
telemt_user_connections_total{user="hello"} 302477
telemt_user_connections_current{user="hello"} 807
telemt_user_octets_from_client{user="hello"} 3566998440 (3.32 GB)
telemt_user_octets_to_client{user="hello"} 112953725720 (105.20 GB)
telemt_user_unique_ips_current{user="hello"} 214
telemt_user_unique_ips_recent_window{user="hello"} 127
```