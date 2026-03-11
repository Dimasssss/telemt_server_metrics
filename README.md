# Server Metrics 2026-03-11 13:14:28 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 82042.8 (22h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1925012
telemt_connections_bad_total 27772
telemt_handshake_timeouts_total 49517
telemt_upstream_connect_attempt_total 17005
telemt_upstream_connect_success_total 16995
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 17004
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8593
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8330
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 71
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 877
telemt_me_reconnect_attempts_total 25662
telemt_me_reconnect_success_total 12829
telemt_me_reader_eof_total 13867
telemt_me_idle_close_by_peer_total 13867
telemt_me_route_drop_no_conn_total 708785
telemt_me_route_drop_channel_closed_total 7
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1757870
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 9196
telemt_desync_full_logged_total 2487
telemt_desync_suppressed_total 6709
telemt_desync_frames_bucket_total{bucket="1_2"} 2288
telemt_desync_frames_bucket_total{bucket="3_10"} 3537
telemt_desync_frames_bucket_total{bucket="gt_10"} 3371
telemt_pool_swap_total 63
telemt_me_writer_removed_unexpected_total 13368
telemt_me_refill_failed_total 398
telemt_me_writer_restored_same_endpoint_total 12823
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 539
telemt_user_connections_total{user="hello"} 1756393
telemt_user_connections_current{user="hello"} 1568
telemt_user_octets_from_client{user="hello"} 23473487524 (21.86 GB)
telemt_user_octets_to_client{user="hello"} 497398199832 (463.24 GB)
telemt_user_unique_ips_current{user="hello"} 384
telemt_user_unique_ips_recent_window{user="hello"} 212
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 82099.5 (22h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 731089
telemt_connections_bad_total 13031
telemt_handshake_timeouts_total 50618
telemt_upstream_connect_attempt_total 26463
telemt_upstream_connect_success_total 23518
telemt_upstream_connect_fail_total 2945
telemt_upstream_connect_attempts_per_request{bucket="1"} 26463
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10840
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10430
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2039
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2945
telemt_me_keepalive_timeout_total 2440
telemt_me_reconnect_attempts_total 17302
telemt_me_reconnect_success_total 16438
telemt_me_reader_eof_total 17404
telemt_me_idle_close_by_peer_total 17401
telemt_me_route_drop_no_conn_total 286223
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 615274
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2700
telemt_desync_full_logged_total 854
telemt_desync_suppressed_total 1846
telemt_desync_frames_bucket_total{bucket="1_2"} 852
telemt_desync_frames_bucket_total{bucket="3_10"} 984
telemt_desync_frames_bucket_total{bucket="gt_10"} 864
telemt_pool_swap_total 69
telemt_me_writer_removed_unexpected_total 16647
telemt_me_refill_failed_total 22
telemt_me_writer_restored_same_endpoint_total 16415
telemt_me_writer_restored_fallback_total 23
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 209
telemt_user_connections_total{user="hello"} 617697
telemt_user_connections_current{user="hello"} 600
telemt_user_octets_from_client{user="hello"} 6607692510 (6.15 GB)
telemt_user_octets_to_client{user="hello"} 176347184452 (164.24 GB)
telemt_user_msgs_from_client{user="hello"} 7933
telemt_user_msgs_to_client{user="hello"} 11226
telemt_user_unique_ips_current{user="hello"} 152
telemt_user_unique_ips_recent_window{user="hello"} 80
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 82099.4 (22h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1257579
telemt_connections_bad_total 8292
telemt_handshake_timeouts_total 116214
telemt_upstream_connect_attempt_total 21947
telemt_upstream_connect_success_total 21680
telemt_upstream_connect_fail_total 267
telemt_upstream_connect_attempts_per_request{bucket="1"} 21947
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11750
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9826
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 104
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 267
telemt_me_keepalive_timeout_total 878
telemt_me_reconnect_attempts_total 32557
telemt_me_reconnect_success_total 16454
telemt_me_reader_eof_total 17711
telemt_me_idle_close_by_peer_total 17711
telemt_me_route_drop_no_conn_total 434928
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1085855
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2919
telemt_desync_full_logged_total 870
telemt_desync_suppressed_total 2049
telemt_desync_frames_bucket_total{bucket="1_2"} 705
telemt_desync_frames_bucket_total{bucket="3_10"} 1099
telemt_desync_frames_bucket_total{bucket="gt_10"} 1115
telemt_pool_swap_total 51
telemt_me_writer_removed_unexpected_total 17175
telemt_me_refill_failed_total 499
telemt_me_writer_restored_same_endpoint_total 16443
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 721
telemt_user_connections_total{user="hello"} 1086240
telemt_user_connections_current{user="hello"} 849
telemt_user_octets_from_client{user="hello"} 12925189109 (12.04 GB)
telemt_user_octets_to_client{user="hello"} 325865677701 (303.49 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 254
telemt_user_unique_ips_recent_window{user="hello"} 138
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 82099.9 (22h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 908901
telemt_connections_bad_total 77080
telemt_handshake_timeouts_total 85967
telemt_upstream_connect_attempt_total 22430
telemt_upstream_connect_success_total 22430
telemt_upstream_connect_attempts_per_request{bucket="1"} 22430
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12292
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10134
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_timeout_total 903
telemt_me_reconnect_attempts_total 19379
telemt_me_reconnect_success_total 18310
telemt_me_reader_eof_total 19420
telemt_me_idle_close_by_peer_total 19419
telemt_me_seq_mismatch_total 17
telemt_me_route_drop_no_conn_total 291585
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 720898
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 28
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1532
telemt_desync_full_logged_total 600
telemt_desync_suppressed_total 932
telemt_desync_frames_bucket_total{bucket="1_2"} 555
telemt_desync_frames_bucket_total{bucket="3_10"} 542
telemt_desync_frames_bucket_total{bucket="gt_10"} 435
telemt_pool_swap_total 72
telemt_me_writer_removed_unexpected_total 18534
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 18282
telemt_me_writer_restored_fallback_total 28
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 224
telemt_user_connections_total{user="hello"} 720256
telemt_user_connections_current{user="hello"} 491
telemt_user_octets_from_client{user="hello"} 8338573036 (7.77 GB)
telemt_user_octets_to_client{user="hello"} 208284054216 (193.98 GB)
telemt_user_unique_ips_current{user="hello"} 146
telemt_user_unique_ips_recent_window{user="hello"} 95
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 82099.4 (22h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 987754
telemt_connections_bad_total 6808
telemt_handshake_timeouts_total 9151
telemt_upstream_connect_attempt_total 22393
telemt_upstream_connect_success_total 22296
telemt_upstream_connect_fail_total 97
telemt_upstream_connect_attempts_per_request{bucket="1"} 22393
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11460
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10650
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 182
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 97
telemt_me_keepalive_timeout_total 933
telemt_me_reconnect_attempts_total 22120
telemt_me_reconnect_success_total 18049
telemt_me_reader_eof_total 19035
telemt_me_idle_close_by_peer_total 19035
telemt_me_route_drop_no_conn_total 348150
telemt_me_route_drop_channel_closed_total 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 896684
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 3616
telemt_desync_full_logged_total 1337
telemt_desync_suppressed_total 2279
telemt_desync_frames_bucket_total{bucket="1_2"} 1261
telemt_desync_frames_bucket_total{bucket="3_10"} 1375
telemt_desync_frames_bucket_total{bucket="gt_10"} 980
telemt_pool_swap_total 55
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 18406
telemt_me_refill_failed_total 124
telemt_me_writer_restored_same_endpoint_total 18049
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 357
telemt_user_connections_total{user="hello"} 896431
telemt_user_connections_current{user="hello"} 708
telemt_user_octets_from_client{user="hello"} 13079626447 (12.18 GB)
telemt_user_octets_to_client{user="hello"} 320831813950 (298.80 GB)
telemt_user_msgs_from_client{user="hello"} 122
telemt_user_msgs_to_client{user="hello"} 215
telemt_user_unique_ips_current{user="hello"} 196
telemt_user_unique_ips_recent_window{user="hello"} 119
```