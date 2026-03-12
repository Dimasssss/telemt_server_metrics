# Server Metrics 2026-03-12 07:11:10 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 4351.1 (1h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 127619
telemt_connections_bad_total 1180
telemt_handshake_timeouts_total 1275
telemt_upstream_connect_attempt_total 924
telemt_upstream_connect_success_total 916
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 924
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 532
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 384
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 7
telemt_me_reconnect_attempts_total 674
telemt_me_reconnect_success_total 671
telemt_me_reader_eof_total 662
telemt_me_idle_close_by_peer_total 662
telemt_me_route_drop_no_conn_total 42502
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 122516
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 670
telemt_desync_full_logged_total 174
telemt_desync_suppressed_total 496
telemt_desync_frames_bucket_total{bucket="1_2"} 148
telemt_desync_frames_bucket_total{bucket="3_10"} 243
telemt_desync_frames_bucket_total{bucket="gt_10"} 279
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 669
telemt_me_writer_restored_same_endpoint_total 658
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_user_connections_total{user="hello"} 122454
telemt_user_connections_current{user="hello"} 1285
telemt_user_octets_from_client{user="hello"} 2177803692 (2.03 GB)
telemt_user_octets_to_client{user="hello"} 37903966952 (35.30 GB)
telemt_user_unique_ips_current{user="hello"} 349
telemt_user_unique_ips_recent_window{user="hello"} 206
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 33971.7 (9h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 154756
telemt_connections_bad_total 2009
telemt_handshake_timeouts_total 6012
telemt_upstream_connect_attempt_total 8829
telemt_upstream_connect_success_total 8824
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 8829
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4389
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4425
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 213
telemt_me_reconnect_attempts_total 6978
telemt_me_reconnect_success_total 6940
telemt_me_reader_eof_total 7381
telemt_me_idle_close_by_peer_total 7381
telemt_me_route_drop_no_conn_total 45225
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 136436
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 399
telemt_desync_full_logged_total 156
telemt_desync_suppressed_total 243
telemt_desync_frames_bucket_total{bucket="1_2"} 112
telemt_desync_frames_bucket_total{bucket="3_10"} 144
telemt_desync_frames_bucket_total{bucket="gt_10"} 143
telemt_pool_swap_total 36
telemt_me_writer_removed_unexpected_total 6997
telemt_me_writer_restored_same_endpoint_total 6931
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 57
telemt_user_connections_total{user="hello"} 136673
telemt_user_connections_current{user="hello"} 458
telemt_user_octets_from_client{user="hello"} 2202678627 (2.05 GB)
telemt_user_octets_to_client{user="hello"} 57141859598 (53.22 GB)
telemt_user_msgs_from_client{user="hello"} 353
telemt_user_msgs_to_client{user="hello"} 423
telemt_user_unique_ips_current{user="hello"} 126
telemt_user_unique_ips_recent_window{user="hello"} 69
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 33971.6 (9h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 505094
telemt_connections_bad_total 2427
telemt_handshake_timeouts_total 37807
telemt_upstream_connect_attempt_total 9101
telemt_upstream_connect_success_total 9099
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 9101
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5091
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3967
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 37
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 144
telemt_me_reconnect_attempts_total 7108
telemt_me_reconnect_success_total 7041
telemt_me_reader_eof_total 7383
telemt_me_idle_close_by_peer_total 7383
telemt_me_route_drop_no_conn_total 87100
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 257053
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1146
telemt_desync_full_logged_total 356
telemt_desync_suppressed_total 790
telemt_desync_frames_bucket_total{bucket="1_2"} 139
telemt_desync_frames_bucket_total{bucket="3_10"} 414
telemt_desync_frames_bucket_total{bucket="gt_10"} 593
telemt_pool_swap_total 35
telemt_me_writer_removed_unexpected_total 7027
telemt_me_refill_failed_total 1
telemt_me_writer_restored_same_endpoint_total 7000
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_user_connections_total{user="hello"} 257346
telemt_user_connections_current{user="hello"} 786
telemt_user_octets_from_client{user="hello"} 2778170212 (2.59 GB)
telemt_user_octets_to_client{user="hello"} 93175140705 (86.78 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 236
telemt_user_unique_ips_recent_window{user="hello"} 137
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 33971.9 (9h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 225824
telemt_connections_bad_total 1741
telemt_handshake_timeouts_total 14298
telemt_upstream_connect_attempt_total 9597
telemt_upstream_connect_success_total 9557
telemt_upstream_connect_fail_total 40
telemt_upstream_connect_attempts_per_request{bucket="1"} 9597
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5486
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4066
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 40
telemt_me_keepalive_timeout_total 251
telemt_me_reconnect_attempts_total 7887
telemt_me_reconnect_success_total 7859
telemt_me_reader_eof_total 8348
telemt_me_idle_close_by_peer_total 8348
telemt_me_route_drop_no_conn_total 73469
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 184436
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 323
telemt_desync_full_logged_total 116
telemt_desync_suppressed_total 207
telemt_desync_frames_bucket_total{bucket="1_2"} 119
telemt_desync_frames_bucket_total{bucket="3_10"} 118
telemt_desync_frames_bucket_total{bucket="gt_10"} 86
telemt_pool_swap_total 34
telemt_me_writer_removed_unexpected_total 7907
telemt_me_writer_restored_same_endpoint_total 7838
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_me_writer_removed_unexpected_minus_restored_total 48
telemt_user_connections_total{user="hello"} 184302
telemt_user_connections_current{user="hello"} 553
telemt_user_octets_from_client{user="hello"} 2114850836 (1.97 GB)
telemt_user_octets_to_client{user="hello"} 58428399212 (54.42 GB)
telemt_user_unique_ips_current{user="hello"} 159
telemt_user_unique_ips_recent_window{user="hello"} 102
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 33971.8 (9h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 240005
telemt_connections_bad_total 317
telemt_handshake_timeouts_total 1606
telemt_upstream_connect_attempt_total 11527
telemt_upstream_connect_success_total 11390
telemt_upstream_connect_fail_total 137
telemt_upstream_connect_attempts_per_request{bucket="1"} 11527
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5916
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5409
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 60
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 137
telemt_me_keepalive_timeout_total 211
telemt_me_reconnect_attempts_total 11191
telemt_me_reconnect_success_total 9679
telemt_me_reader_eof_total 10074
telemt_me_idle_close_by_peer_total 10074
telemt_me_seq_mismatch_total 15
telemt_me_route_drop_no_conn_total 74932
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 226910
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 905
telemt_desync_full_logged_total 304
telemt_desync_suppressed_total 601
telemt_desync_frames_bucket_total{bucket="1_2"} 218
telemt_desync_frames_bucket_total{bucket="3_10"} 339
telemt_desync_frames_bucket_total{bucket="gt_10"} 348
telemt_pool_swap_total 20
telemt_me_writer_removed_unexpected_total 9817
telemt_me_refill_failed_total 46
telemt_me_writer_restored_same_endpoint_total 9659
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 138
telemt_user_connections_total{user="hello"} 226864
telemt_user_connections_current{user="hello"} 592
telemt_user_octets_from_client{user="hello"} 2115874772 (1.97 GB)
telemt_user_octets_to_client{user="hello"} 53653851736 (49.97 GB)
telemt_user_unique_ips_current{user="hello"} 177
telemt_user_unique_ips_recent_window{user="hello"} 96
```