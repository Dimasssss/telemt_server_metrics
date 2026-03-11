# Server Metrics 2026-03-11 21:39:51 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 112365.1 (31h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2826739
telemt_connections_bad_total 66253
telemt_handshake_timeouts_total 62638
telemt_upstream_connect_attempt_total 23973
telemt_upstream_connect_success_total 23961
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 23973
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12117
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11729
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 114
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_keepalive_timeout_total 5444
telemt_me_reconnect_attempts_total 36182
telemt_me_reconnect_success_total 18280
telemt_me_reader_eof_total 19725
telemt_me_idle_close_by_peer_total 19725
telemt_me_route_drop_no_conn_total 1059195
telemt_me_route_drop_channel_closed_total 10
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2561114
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 12751
telemt_desync_full_logged_total 3543
telemt_desync_suppressed_total 9208
telemt_desync_frames_bucket_total{bucket="1_2"} 3150
telemt_desync_frames_bucket_total{bucket="3_10"} 4890
telemt_desync_frames_bucket_total{bucket="gt_10"} 4711
telemt_pool_swap_total 80
telemt_me_writer_removed_unexpected_total 19052
telemt_me_refill_failed_total 555
telemt_me_writer_restored_same_endpoint_total 18274
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 772
telemt_user_connections_total{user="hello"} 2559447
telemt_user_connections_current{user="hello"} 651
telemt_user_octets_from_client{user="hello"} 38870867428 (36.20 GB)
telemt_user_octets_to_client{user="hello"} 739480975064 (688.70 GB)
telemt_user_unique_ips_current{user="hello"} 220
telemt_user_unique_ips_recent_window{user="hello"} 65
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 112421.7 (31h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1030214
telemt_connections_bad_total 17056
telemt_handshake_timeouts_total 90603
telemt_upstream_connect_attempt_total 34586
telemt_upstream_connect_success_total 31595
telemt_upstream_connect_fail_total 2991
telemt_upstream_connect_attempts_per_request{bucket="1"} 34586
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15107
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14186
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2093
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2991
telemt_me_keepalive_timeout_total 6549
telemt_me_reconnect_attempts_total 24858
telemt_me_reconnect_success_total 22714
telemt_me_reader_eof_total 24002
telemt_me_idle_close_by_peer_total 23999
telemt_me_route_drop_no_conn_total 388970
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 862307
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3385
telemt_desync_full_logged_total 1103
telemt_desync_suppressed_total 2282
telemt_desync_frames_bucket_total{bucket="1_2"} 1108
telemt_desync_frames_bucket_total{bucket="3_10"} 1194
telemt_desync_frames_bucket_total{bucket="gt_10"} 1083
telemt_pool_swap_total 92
telemt_me_writer_removed_unexpected_total 22994
telemt_me_refill_failed_total 60
telemt_me_writer_restored_same_endpoint_total 22691
telemt_me_writer_restored_fallback_total 23
telemt_me_async_recovery_trigger_total 141
telemt_me_writer_removed_unexpected_minus_restored_total 280
telemt_user_connections_total{user="hello"} 865035
telemt_user_connections_current{user="hello"} 244
telemt_user_octets_from_client{user="hello"} 10444702509 (9.73 GB)
telemt_user_octets_to_client{user="hello"} 261384084436 (243.43 GB)
telemt_user_msgs_from_client{user="hello"} 8579
telemt_user_msgs_to_client{user="hello"} 12990
telemt_user_unique_ips_current{user="hello"} 86
telemt_user_unique_ips_recent_window{user="hello"} 38
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 112421.6 (31h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1800599
telemt_connections_bad_total 11437
telemt_handshake_timeouts_total 138123
telemt_upstream_connect_attempt_total 50031
telemt_upstream_connect_success_total 49671
telemt_upstream_connect_fail_total 360
telemt_upstream_connect_attempts_per_request{bucket="1"} 50031
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 35960
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13554
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 151
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 360
telemt_me_keepalive_timeout_total 2060
telemt_me_reconnect_attempts_total 63979
telemt_me_reconnect_success_total 20719
telemt_me_reader_eof_total 22930
telemt_me_idle_close_by_peer_total 22930
telemt_me_route_drop_no_conn_total 646988
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1562085
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4215
telemt_desync_full_logged_total 1244
telemt_desync_suppressed_total 2971
telemt_desync_frames_bucket_total{bucket="1_2"} 986
telemt_desync_frames_bucket_total{bucket="3_10"} 1604
telemt_desync_frames_bucket_total{bucket="gt_10"} 1625
telemt_pool_swap_total 55
telemt_me_writer_removed_unexpected_total 22353
telemt_me_refill_failed_total 1346
telemt_me_writer_restored_same_endpoint_total 20707
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 1634
telemt_user_connections_total{user="hello"} 1583909
telemt_user_connections_current{user="hello"} 399
telemt_user_octets_from_client{user="hello"} 20109670093 (18.73 GB)
telemt_user_octets_to_client{user="hello"} 483683805145 (450.47 GB)
telemt_user_msgs_from_client{user="hello"} 275413
telemt_user_msgs_to_client{user="hello"} 1868730
telemt_user_unique_ips_current{user="hello"} 124
telemt_user_unique_ips_recent_window{user="hello"} 49
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 112422.1 (31h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1288775
telemt_connections_bad_total 78307
telemt_handshake_timeouts_total 112050
telemt_upstream_connect_attempt_total 30063
telemt_upstream_connect_success_total 30063
telemt_upstream_connect_attempts_per_request{bucket="1"} 30063
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16358
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13698
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_me_keepalive_timeout_total 1556
telemt_me_reconnect_attempts_total 29075
telemt_me_reconnect_success_total 24454
telemt_me_reader_eof_total 25974
telemt_me_idle_close_by_peer_total 25973
telemt_me_seq_mismatch_total 23
telemt_me_route_drop_no_conn_total 431817
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1062330
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 34
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2212
telemt_desync_full_logged_total 832
telemt_desync_suppressed_total 1380
telemt_desync_frames_bucket_total{bucket="1_2"} 781
telemt_desync_frames_bucket_total{bucket="3_10"} 743
telemt_desync_frames_bucket_total{bucket="gt_10"} 688
telemt_pool_swap_total 92
telemt_me_writer_removed_unexpected_total 24861
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 24421
telemt_me_writer_restored_fallback_total 33
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 407
telemt_user_connections_total{user="hello"} 1061450
telemt_user_connections_current{user="hello"} 266
telemt_user_octets_from_client{user="hello"} 12374675712 (11.52 GB)
telemt_user_octets_to_client{user="hello"} 320081712480 (298.10 GB)
telemt_user_unique_ips_current{user="hello"} 92
telemt_user_unique_ips_recent_window{user="hello"} 37
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 17098.0 (4h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 224113
telemt_connections_bad_total 5184
telemt_handshake_timeouts_total 2531
telemt_upstream_connect_attempt_total 4936
telemt_upstream_connect_success_total 4935
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 4936
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2533
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2376
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 26
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 105
telemt_me_reconnect_attempts_total 4069
telemt_me_reconnect_success_total 4031
telemt_me_reader_eof_total 4174
telemt_me_idle_close_by_peer_total 4174
telemt_me_seq_mismatch_total 5
telemt_me_route_drop_no_conn_total 75642
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 198949
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 27
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 499
telemt_desync_full_logged_total 177
telemt_desync_suppressed_total 322
telemt_desync_frames_bucket_total{bucket="1_2"} 132
telemt_desync_frames_bucket_total{bucket="3_10"} 176
telemt_desync_frames_bucket_total{bucket="gt_10"} 191
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 4078
telemt_me_writer_restored_same_endpoint_total 4004
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 256
telemt_me_writer_removed_unexpected_minus_restored_total 47
telemt_user_connections_total{user="hello"} 198911
telemt_user_connections_current{user="hello"} 312
telemt_user_octets_from_client{user="hello"} 9748604224 (9.08 GB)
telemt_user_octets_to_client{user="hello"} 69384100512 (64.62 GB)
telemt_user_unique_ips_current{user="hello"} 101
telemt_user_unique_ips_recent_window{user="hello"} 35
```