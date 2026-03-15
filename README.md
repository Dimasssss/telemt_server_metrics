# Server Metrics 2026-03-15 10:50:48 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.18

telemt_uptime_seconds 45378.7 (12h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1129684
telemt_connections_bad_total 68316
telemt_handshake_timeouts_total 9310
telemt_upstream_connect_attempt_total 9131
telemt_upstream_connect_success_total 9092
telemt_upstream_connect_fail_total 39
telemt_upstream_connect_attempts_per_request{bucket="1"} 9131
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4822
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4246
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 24
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 39
telemt_me_keepalive_timeout_total 8
telemt_me_reconnect_attempts_total 9315
telemt_me_reconnect_success_total 6811
telemt_me_reader_eof_total 7265
telemt_me_idle_close_by_peer_total 7265
telemt_me_route_drop_no_conn_total 377706
telemt_me_route_drop_channel_closed_total 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 954027
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3591
telemt_desync_full_logged_total 1012
telemt_desync_suppressed_total 2579
telemt_desync_frames_bucket_total{bucket="1_2"} 890
telemt_desync_frames_bucket_total{bucket="3_10"} 1394
telemt_desync_frames_bucket_total{bucket="gt_10"} 1307
telemt_pool_swap_total 38
telemt_me_writer_removed_unexpected_total 6986
telemt_me_refill_failed_total 77
telemt_me_writer_restored_same_endpoint_total 6800
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 296
telemt_me_writer_removed_unexpected_minus_restored_total 175
telemt_user_connections_total{user="hello"} 954022
telemt_user_connections_current{user="hello"} 2089
telemt_user_octets_from_client{user="hello"} 13522552920 (12.59 GB)
telemt_user_octets_to_client{user="hello"} 383838496428 (357.48 GB)
telemt_user_unique_ips_current{user="hello"} 563
telemt_user_unique_ips_recent_window{user="hello"} 255
```

## server2

```
telemt 3.3.18

telemt_uptime_seconds 45379.5 (12h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 443942
telemt_connections_bad_total 24216
telemt_handshake_timeouts_total 18291
telemt_upstream_connect_attempt_total 12079
telemt_upstream_connect_success_total 12015
telemt_upstream_connect_fail_total 64
telemt_upstream_connect_attempts_per_request{bucket="1"} 12079
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6509
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5403
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 30
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 73
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 64
telemt_me_keepalive_timeout_total 15
telemt_me_reconnect_attempts_total 9469
telemt_me_reconnect_success_total 9409
telemt_me_reader_eof_total 9959
telemt_me_idle_close_by_peer_total 9959
telemt_me_route_drop_no_conn_total 113337
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 351321
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 16
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1240
telemt_desync_full_logged_total 433
telemt_desync_suppressed_total 807
telemt_desync_frames_bucket_total{bucket="1_2"} 434
telemt_desync_frames_bucket_total{bucket="3_10"} 451
telemt_desync_frames_bucket_total{bucket="gt_10"} 355
telemt_pool_swap_total 41
telemt_me_writer_removed_unexpected_total 9505
telemt_me_writer_restored_same_endpoint_total 9401
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 61
telemt_me_writer_removed_unexpected_minus_restored_total 96
telemt_user_connections_total{user="hello"} 351605
telemt_user_connections_current{user="hello"} 656
telemt_user_octets_from_client{user="hello"} 5064582671 (4.72 GB)
telemt_user_octets_to_client{user="hello"} 132241864948 (123.16 GB)
telemt_user_msgs_from_client{user="hello"} 620
telemt_user_msgs_to_client{user="hello"} 1332
telemt_user_unique_ips_current{user="hello"} 211
telemt_user_unique_ips_recent_window{user="hello"} 109
```

## server3

```
telemt 3.3.18

telemt_uptime_seconds 45379.6 (12h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 854526
telemt_connections_bad_total 28494
telemt_handshake_timeouts_total 83872
telemt_upstream_connect_attempt_total 10035
telemt_upstream_connect_success_total 9992
telemt_upstream_connect_fail_total 43
telemt_upstream_connect_attempts_per_request{bucket="1"} 10035
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5181
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4755
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 56
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 43
telemt_me_reconnect_attempts_total 7751
telemt_me_reconnect_success_total 7700
telemt_me_reader_eof_total 8155
telemt_me_idle_close_by_peer_total 8155
telemt_me_route_drop_no_conn_total 233032
telemt_me_route_drop_channel_closed_total 15
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 616547
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1436
telemt_desync_full_logged_total 520
telemt_desync_suppressed_total 916
telemt_desync_frames_bucket_total{bucket="1_2"} 314
telemt_desync_frames_bucket_total{bucket="3_10"} 524
telemt_desync_frames_bucket_total{bucket="gt_10"} 598
telemt_pool_swap_total 44
telemt_me_writer_removed_unexpected_total 7802
telemt_me_writer_restored_same_endpoint_total 7681
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 242
telemt_me_writer_removed_unexpected_minus_restored_total 102
telemt_user_connections_total{user="hello"} 615971
telemt_user_connections_current{user="hello"} 1259
telemt_user_octets_from_client{user="hello"} 9077534124 (8.45 GB)
telemt_user_octets_to_client{user="hello"} 243539480124 (226.81 GB)
telemt_user_unique_ips_current{user="hello"} 360
telemt_user_unique_ips_recent_window{user="hello"} 162
```

## server4

```
telemt 3.3.18

telemt_uptime_seconds 45379.3 (12h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 460189
telemt_connections_bad_total 57080
telemt_handshake_timeouts_total 26091
telemt_upstream_connect_attempt_total 13631
telemt_upstream_connect_success_total 13288
telemt_upstream_connect_fail_total 343
telemt_upstream_connect_attempts_per_request{bucket="1"} 13631
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6342
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6943
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 343
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 31366
telemt_me_reconnect_success_total 11003
telemt_me_reader_eof_total 11967
telemt_me_idle_close_by_peer_total 11967
telemt_me_seq_mismatch_total 17
telemt_me_route_drop_no_conn_total 128799
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 345949
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 34
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 817
telemt_desync_full_logged_total 207
telemt_desync_suppressed_total 610
telemt_desync_frames_bucket_total{bucket="1_2"} 200
telemt_desync_frames_bucket_total{bucket="3_10"} 325
telemt_desync_frames_bucket_total{bucket="gt_10"} 292
telemt_pool_swap_total 17
telemt_me_writer_removed_unexpected_total 11740
telemt_me_refill_failed_total 636
telemt_me_writer_restored_same_endpoint_total 10971
telemt_me_writer_restored_fallback_total 32
telemt_me_async_recovery_trigger_total 96
telemt_me_writer_removed_unexpected_minus_restored_total 737
telemt_user_connections_total{user="hello"} 345856
telemt_user_connections_current{user="hello"} 641
telemt_user_octets_from_client{user="hello"} 4098090432 (3.82 GB)
telemt_user_octets_to_client{user="hello"} 109048567212 (101.56 GB)
telemt_user_unique_ips_current{user="hello"} 205
telemt_user_unique_ips_recent_window{user="hello"} 105
```

## server5

```
telemt 3.3.18

telemt_uptime_seconds 45380.2 (12h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 470824
telemt_connections_bad_total 6153
telemt_handshake_timeouts_total 8232
telemt_upstream_connect_attempt_total 10045
telemt_upstream_connect_success_total 9997
telemt_upstream_connect_fail_total 48
telemt_upstream_connect_attempts_per_request{bucket="1"} 10045
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4559
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5433
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 48
telemt_me_reconnect_attempts_total 7761
telemt_me_reconnect_success_total 7721
telemt_me_reader_eof_total 8206
telemt_me_idle_close_by_peer_total 8206
telemt_me_route_drop_no_conn_total 122688
telemt_me_route_drop_channel_closed_total 14
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 389359
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1523
telemt_desync_full_logged_total 488
telemt_desync_suppressed_total 1035
telemt_desync_frames_bucket_total{bucket="1_2"} 442
telemt_desync_frames_bucket_total{bucket="3_10"} 626
telemt_desync_frames_bucket_total{bucket="gt_10"} 455
telemt_pool_swap_total 43
telemt_me_writer_removed_unexpected_total 7808
telemt_me_writer_restored_same_endpoint_total 7713
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 54
telemt_me_writer_removed_unexpected_minus_restored_total 87
telemt_user_connections_total{user="hello"} 389375
telemt_user_connections_current{user="hello"} 859
telemt_user_octets_from_client{user="hello"} 4821586960 (4.49 GB)
telemt_user_octets_to_client{user="hello"} 145930177812 (135.91 GB)
telemt_user_unique_ips_current{user="hello"} 223
telemt_user_unique_ips_recent_window{user="hello"} 110
```