# Server Metrics 2026-03-15 17:44:37 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.18

telemt_uptime_seconds 70207.3 (19h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2469924
telemt_connections_bad_total 149148
telemt_handshake_timeouts_total 32073
telemt_upstream_connect_attempt_total 13615
telemt_upstream_connect_success_total 13556
telemt_upstream_connect_fail_total 59
telemt_upstream_connect_attempts_per_request{bucket="1"} 13615
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7031
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6456
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 69
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 59
telemt_me_keepalive_timeout_total 55
telemt_me_reconnect_attempts_total 14958
telemt_me_reconnect_success_total 10061
telemt_me_reader_eof_total 10755
telemt_me_idle_close_by_peer_total 10755
telemt_me_route_drop_no_conn_total 852883
telemt_me_route_drop_channel_closed_total 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2062532
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8027
telemt_desync_full_logged_total 2177
telemt_desync_suppressed_total 5850
telemt_desync_frames_bucket_total{bucket="1_2"} 1958
telemt_desync_frames_bucket_total{bucket="3_10"} 3080
telemt_desync_frames_bucket_total{bucket="gt_10"} 2989
telemt_pool_swap_total 53
telemt_me_writer_removed_unexpected_total 10385
telemt_me_refill_failed_total 151
telemt_me_writer_restored_same_endpoint_total 10050
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 296
telemt_me_writer_removed_unexpected_minus_restored_total 324
telemt_user_connections_total{user="hello"} 2062017
telemt_user_connections_current{user="hello"} 2300
telemt_user_octets_from_client{user="hello"} 30515330124 (28.42 GB)
telemt_user_octets_to_client{user="hello"} 784333763920 (730.47 GB)
telemt_user_unique_ips_current{user="hello"} 664
telemt_user_unique_ips_recent_window{user="hello"} 284
```

## server2

```
telemt 3.3.18

telemt_uptime_seconds 70208.1 (19h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 955826
telemt_connections_bad_total 52514
telemt_handshake_timeouts_total 62610
telemt_upstream_connect_attempt_total 17515
telemt_upstream_connect_success_total 17421
telemt_upstream_connect_fail_total 94
telemt_upstream_connect_attempts_per_request{bucket="1"} 17515
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9261
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7988
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 40
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 132
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 94
telemt_me_keepalive_timeout_total 59
telemt_me_reconnect_attempts_total 14775
telemt_me_reconnect_success_total 13566
telemt_me_reader_eof_total 14349
telemt_me_idle_close_by_peer_total 14349
telemt_me_route_drop_no_conn_total 246823
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 738897
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 16
telemt_me_endpoint_quarantine_total 17
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2194
telemt_desync_full_logged_total 740
telemt_desync_suppressed_total 1454
telemt_desync_frames_bucket_total{bucket="1_2"} 777
telemt_desync_frames_bucket_total{bucket="3_10"} 827
telemt_desync_frames_bucket_total{bucket="gt_10"} 590
telemt_pool_swap_total 57
telemt_me_writer_removed_unexpected_total 13780
telemt_me_refill_failed_total 34
telemt_me_writer_restored_same_endpoint_total 13554
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 61
telemt_me_writer_removed_unexpected_minus_restored_total 214
telemt_user_connections_total{user="hello"} 739128
telemt_user_connections_current{user="hello"} 825
telemt_user_octets_from_client{user="hello"} 10750845687 (10.01 GB)
telemt_user_octets_to_client{user="hello"} 278275202492 (259.16 GB)
telemt_user_msgs_from_client{user="hello"} 620
telemt_user_msgs_to_client{user="hello"} 1332
telemt_user_unique_ips_current{user="hello"} 242
telemt_user_unique_ips_recent_window{user="hello"} 120
```

## server3

```
telemt 3.3.18

telemt_uptime_seconds 70208.3 (19h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2123652
telemt_connections_bad_total 50219
telemt_handshake_timeouts_total 214105
telemt_upstream_connect_attempt_total 15132
telemt_upstream_connect_success_total 15059
telemt_upstream_connect_fail_total 73
telemt_upstream_connect_attempts_per_request{bucket="1"} 15132
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7774
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7211
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 74
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 73
telemt_me_keepalive_timeout_total 45
telemt_me_reconnect_attempts_total 12801
telemt_me_reconnect_success_total 11532
telemt_me_reader_eof_total 12219
telemt_me_idle_close_by_peer_total 12219
telemt_me_route_drop_no_conn_total 550320
telemt_me_route_drop_channel_closed_total 19
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1316183
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3379
telemt_desync_full_logged_total 1219
telemt_desync_suppressed_total 2160
telemt_desync_frames_bucket_total{bucket="1_2"} 773
telemt_desync_frames_bucket_total{bucket="3_10"} 1310
telemt_desync_frames_bucket_total{bucket="gt_10"} 1296
telemt_pool_swap_total 60
telemt_me_writer_removed_unexpected_total 11736
telemt_me_refill_failed_total 37
telemt_me_writer_restored_same_endpoint_total 11513
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 242
telemt_me_writer_removed_unexpected_minus_restored_total 204
telemt_user_connections_total{user="hello"} 1312095
telemt_user_connections_current{user="hello"} 1470
telemt_user_octets_from_client{user="hello"} 23581927628 (21.96 GB)
telemt_user_octets_to_client{user="hello"} 479172705300 (446.26 GB)
telemt_user_unique_ips_current{user="hello"} 434
telemt_user_unique_ips_recent_window{user="hello"} 191
```

## server4

```
telemt 3.3.18

telemt_uptime_seconds 70207.9 (19h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1022281
telemt_connections_bad_total 82047
telemt_handshake_timeouts_total 49721
telemt_upstream_connect_attempt_total 170484
telemt_upstream_connect_success_total 169900
telemt_upstream_connect_fail_total 584
telemt_upstream_connect_attempts_per_request{bucket="1"} 170484
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 156665
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13176
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 59
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 584
telemt_me_keepalive_timeout_total 39
telemt_me_reconnect_attempts_total 61497
telemt_me_reconnect_success_total 13433
telemt_me_reader_eof_total 15294
telemt_me_idle_close_by_peer_total 15294
telemt_me_seq_mismatch_total 27
telemt_me_route_drop_no_conn_total 240289
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 639854
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 44
telemt_me_hardswap_pending_ttl_expired_total 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1808
telemt_desync_full_logged_total 493
telemt_desync_suppressed_total 1315
telemt_desync_frames_bucket_total{bucket="1_2"} 462
telemt_desync_frames_bucket_total{bucket="3_10"} 703
telemt_desync_frames_bucket_total{bucket="gt_10"} 643
telemt_pool_swap_total 19
telemt_me_writer_removed_unexpected_total 15077
telemt_me_refill_failed_total 1504
telemt_me_writer_restored_same_endpoint_total 13397
telemt_me_writer_restored_fallback_total 36
telemt_me_async_recovery_trigger_total 96
telemt_me_writer_removed_unexpected_minus_restored_total 1644
telemt_user_connections_total{user="hello"} 792371
telemt_user_connections_current{user="hello"} 854
telemt_user_octets_from_client{user="hello"} 14609669489 (13.61 GB)
telemt_user_octets_to_client{user="hello"} 283166007504 (263.72 GB)
telemt_user_msgs_from_client{user="hello"} 3035962
telemt_user_msgs_to_client{user="hello"} 10927629
telemt_user_unique_ips_current{user="hello"} 243
telemt_user_unique_ips_recent_window{user="hello"} 117
```

## server5

```
telemt 3.3.18

telemt_uptime_seconds 70209.0 (19h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1035439
telemt_connections_bad_total 12421
telemt_handshake_timeouts_total 23106
telemt_upstream_connect_attempt_total 15426
telemt_upstream_connect_success_total 15343
telemt_upstream_connect_fail_total 83
telemt_upstream_connect_attempts_per_request{bucket="1"} 15426
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7103
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8221
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 19
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 83
telemt_me_keepalive_timeout_total 88
telemt_me_reconnect_attempts_total 15533
telemt_me_reconnect_success_total 11838
telemt_me_reader_eof_total 12627
telemt_me_idle_close_by_peer_total 12627
telemt_me_route_drop_no_conn_total 258219
telemt_me_route_drop_channel_closed_total 29
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 857398
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2908
telemt_desync_full_logged_total 974
telemt_desync_suppressed_total 1934
telemt_desync_frames_bucket_total{bucket="1_2"} 891
telemt_desync_frames_bucket_total{bucket="3_10"} 1084
telemt_desync_frames_bucket_total{bucket="gt_10"} 933
telemt_pool_swap_total 58
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 12097
telemt_me_refill_failed_total 113
telemt_me_writer_restored_same_endpoint_total 11830
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 54
telemt_me_writer_removed_unexpected_minus_restored_total 259
telemt_user_connections_total{user="hello"} 857423
telemt_user_connections_current{user="hello"} 997
telemt_user_octets_from_client{user="hello"} 10701037136 (9.97 GB)
telemt_user_octets_to_client{user="hello"} 301041221228 (280.37 GB)
telemt_user_unique_ips_current{user="hello"} 242
telemt_user_unique_ips_recent_window{user="hello"} 112
```