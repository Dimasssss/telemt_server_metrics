# Server Metrics 2026-03-15 16:43:18 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.18

telemt_uptime_seconds 66527.5 (18h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2254209
telemt_connections_bad_total 132468
telemt_handshake_timeouts_total 27955
telemt_upstream_connect_attempt_total 13086
telemt_upstream_connect_success_total 13030
telemt_upstream_connect_fail_total 56
telemt_upstream_connect_attempts_per_request{bucket="1"} 13086
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6772
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6201
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 57
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 56
telemt_me_keepalive_timeout_total 47
telemt_me_reconnect_attempts_total 14604
telemt_me_reconnect_success_total 9708
telemt_me_reader_eof_total 10376
telemt_me_idle_close_by_peer_total 10376
telemt_me_route_drop_no_conn_total 778656
telemt_me_route_drop_channel_closed_total 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1896165
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7439
telemt_desync_full_logged_total 2039
telemt_desync_suppressed_total 5400
telemt_desync_frames_bucket_total{bucket="1_2"} 1804
telemt_desync_frames_bucket_total{bucket="3_10"} 2854
telemt_desync_frames_bucket_total{bucket="gt_10"} 2781
telemt_pool_swap_total 49
telemt_me_writer_removed_unexpected_total 10022
telemt_me_refill_failed_total 151
telemt_me_writer_restored_same_endpoint_total 9697
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 296
telemt_me_writer_removed_unexpected_minus_restored_total 314
telemt_user_connections_total{user="hello"} 1895663
telemt_user_connections_current{user="hello"} 2547
telemt_user_octets_from_client{user="hello"} 27859724016 (25.95 GB)
telemt_user_octets_to_client{user="hello"} 722750354804 (673.11 GB)
telemt_user_unique_ips_current{user="hello"} 695
telemt_user_unique_ips_recent_window{user="hello"} 295
```

## server2

```
telemt 3.3.18

telemt_uptime_seconds 66528.3 (18h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 881132
telemt_connections_bad_total 47424
telemt_handshake_timeouts_total 60957
telemt_upstream_connect_attempt_total 16803
telemt_upstream_connect_success_total 16722
telemt_upstream_connect_fail_total 81
telemt_upstream_connect_attempts_per_request{bucket="1"} 16803
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8916
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7646
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 38
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 122
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 81
telemt_me_keepalive_timeout_total 59
telemt_me_reconnect_attempts_total 14243
telemt_me_reconnect_success_total 13049
telemt_me_reader_eof_total 13797
telemt_me_idle_close_by_peer_total 13797
telemt_me_route_drop_no_conn_total 225755
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 675955
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 16
telemt_me_endpoint_quarantine_total 17
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2125
telemt_desync_full_logged_total 719
telemt_desync_suppressed_total 1406
telemt_desync_frames_bucket_total{bucket="1_2"} 769
telemt_desync_frames_bucket_total{bucket="3_10"} 787
telemt_desync_frames_bucket_total{bucket="gt_10"} 569
telemt_pool_swap_total 53
telemt_me_writer_removed_unexpected_total 13253
telemt_me_refill_failed_total 34
telemt_me_writer_restored_same_endpoint_total 13037
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 61
telemt_me_writer_removed_unexpected_minus_restored_total 204
telemt_user_connections_total{user="hello"} 676198
telemt_user_connections_current{user="hello"} 707
telemt_user_octets_from_client{user="hello"} 9732136639 (9.06 GB)
telemt_user_octets_to_client{user="hello"} 255676460024 (238.12 GB)
telemt_user_msgs_from_client{user="hello"} 620
telemt_user_msgs_to_client{user="hello"} 1332
telemt_user_unique_ips_current{user="hello"} 244
telemt_user_unique_ips_recent_window{user="hello"} 118
```

## server3

```
telemt 3.3.18

telemt_uptime_seconds 66528.4 (18h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1989284
telemt_connections_bad_total 48400
telemt_handshake_timeouts_total 196153
telemt_upstream_connect_attempt_total 14523
telemt_upstream_connect_success_total 14454
telemt_upstream_connect_fail_total 69
telemt_upstream_connect_attempts_per_request{bucket="1"} 14523
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7455
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6930
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 69
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 69
telemt_me_keepalive_timeout_total 45
telemt_me_reconnect_attempts_total 12368
telemt_me_reconnect_success_total 11100
telemt_me_reader_eof_total 11745
telemt_me_idle_close_by_peer_total 11745
telemt_me_route_drop_no_conn_total 513750
telemt_me_route_drop_channel_closed_total 18
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1206704
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3089
telemt_desync_full_logged_total 1110
telemt_desync_suppressed_total 1979
telemt_desync_frames_bucket_total{bucket="1_2"} 719
telemt_desync_frames_bucket_total{bucket="3_10"} 1187
telemt_desync_frames_bucket_total{bucket="gt_10"} 1183
telemt_pool_swap_total 56
telemt_me_writer_removed_unexpected_total 11296
telemt_me_refill_failed_total 37
telemt_me_writer_restored_same_endpoint_total 11081
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 242
telemt_me_writer_removed_unexpected_minus_restored_total 196
telemt_user_connections_total{user="hello"} 1202669
telemt_user_connections_current{user="hello"} 1423
telemt_user_octets_from_client{user="hello"} 17528464980 (16.32 GB)
telemt_user_octets_to_client{user="hello"} 432863922732 (403.14 GB)
telemt_user_unique_ips_current{user="hello"} 423
telemt_user_unique_ips_recent_window{user="hello"} 202
```

## server4

```
telemt 3.3.18

telemt_uptime_seconds 66528.2 (18h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 937922
telemt_connections_bad_total 79757
telemt_handshake_timeouts_total 46329
telemt_upstream_connect_attempt_total 169063
telemt_upstream_connect_success_total 168534
telemt_upstream_connect_fail_total 529
telemt_upstream_connect_attempts_per_request{bucket="1"} 169063
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 155527
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12972
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 35
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 529
telemt_me_keepalive_timeout_total 39
telemt_me_reconnect_attempts_total 55975
telemt_me_reconnect_success_total 13145
telemt_me_reader_eof_total 14841
telemt_me_idle_close_by_peer_total 14841
telemt_me_seq_mismatch_total 26
telemt_me_route_drop_no_conn_total 214773
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 573007
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 43
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1626
telemt_desync_full_logged_total 423
telemt_desync_suppressed_total 1203
telemt_desync_frames_bucket_total{bucket="1_2"} 420
telemt_desync_frames_bucket_total{bucket="3_10"} 638
telemt_desync_frames_bucket_total{bucket="gt_10"} 568
telemt_pool_swap_total 19
telemt_me_writer_removed_unexpected_total 14618
telemt_me_refill_failed_total 1340
telemt_me_writer_restored_same_endpoint_total 13109
telemt_me_writer_restored_fallback_total 36
telemt_me_async_recovery_trigger_total 96
telemt_me_writer_removed_unexpected_minus_restored_total 1473
telemt_user_connections_total{user="hello"} 724631
telemt_user_connections_current{user="hello"} 909
telemt_user_octets_from_client{user="hello"} 13798914222 (12.85 GB)
telemt_user_octets_to_client{user="hello"} 259035567165 (241.25 GB)
telemt_user_msgs_from_client{user="hello"} 3034166
telemt_user_msgs_to_client{user="hello"} 10923814
telemt_user_unique_ips_current{user="hello"} 252
telemt_user_unique_ips_recent_window{user="hello"} 135
```

## server5

```
telemt 3.3.18

telemt_uptime_seconds 66529.3 (18h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 952036
telemt_connections_bad_total 12054
telemt_handshake_timeouts_total 20888
telemt_upstream_connect_attempt_total 14825
telemt_upstream_connect_success_total 14745
telemt_upstream_connect_fail_total 80
telemt_upstream_connect_attempts_per_request{bucket="1"} 14825
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6805
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7926
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 80
telemt_me_keepalive_timeout_total 86
telemt_me_reconnect_attempts_total 15106
telemt_me_reconnect_success_total 11417
telemt_me_reader_eof_total 12175
telemt_me_idle_close_by_peer_total 12175
telemt_me_route_drop_no_conn_total 237573
telemt_me_route_drop_channel_closed_total 28
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 786993
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2701
telemt_desync_full_logged_total 908
telemt_desync_suppressed_total 1793
telemt_desync_frames_bucket_total{bucket="1_2"} 840
telemt_desync_frames_bucket_total{bucket="3_10"} 1014
telemt_desync_frames_bucket_total{bucket="gt_10"} 847
telemt_pool_swap_total 54
telemt_me_writer_removed_unexpected_total 11669
telemt_me_refill_failed_total 113
telemt_me_writer_restored_same_endpoint_total 11409
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 54
telemt_me_writer_removed_unexpected_minus_restored_total 252
telemt_user_connections_total{user="hello"} 787039
telemt_user_connections_current{user="hello"} 926
telemt_user_octets_from_client{user="hello"} 9723706668 (9.06 GB)
telemt_user_octets_to_client{user="hello"} 280398818432 (261.14 GB)
telemt_user_unique_ips_current{user="hello"} 259
telemt_user_unique_ips_recent_window{user="hello"} 132
```