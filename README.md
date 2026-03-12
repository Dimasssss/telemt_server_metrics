# Server Metrics 2026-03-12 18:29:48 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 45068.1 (12h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1614920
telemt_connections_bad_total 20490
telemt_handshake_timeouts_total 14953
telemt_upstream_connect_attempt_total 8967
telemt_upstream_connect_success_total 8916
telemt_upstream_connect_fail_total 51
telemt_upstream_connect_attempts_per_request{bucket="1"} 8967
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4656
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4231
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 29
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 51
telemt_me_keepalive_timeout_total 559
telemt_me_reconnect_attempts_total 15463
telemt_me_reconnect_success_total 6618
telemt_me_reader_eof_total 7167
telemt_me_idle_close_by_peer_total 7166
telemt_me_route_drop_no_conn_total 630997
telemt_me_route_drop_channel_closed_total 10
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1512558
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7732
telemt_desync_full_logged_total 1962
telemt_desync_suppressed_total 5770
telemt_desync_frames_bucket_total{bucket="1_2"} 2008
telemt_desync_frames_bucket_total{bucket="3_10"} 2809
telemt_desync_frames_bucket_total{bucket="gt_10"} 2915
telemt_pool_swap_total 26
telemt_me_writer_removed_unexpected_total 6988
telemt_me_refill_failed_total 275
telemt_me_writer_restored_same_endpoint_total 6605
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 370
telemt_user_connections_total{user="hello"} 1512046
telemt_user_connections_current{user="hello"} 1520
telemt_user_octets_from_client{user="hello"} 23494201928 (21.88 GB)
telemt_user_octets_to_client{user="hello"} 505884199880 (471.14 GB)
telemt_user_unique_ips_current{user="hello"} 407
telemt_user_unique_ips_recent_window{user="hello"} 183
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 74688.4 (20h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 695036
telemt_connections_bad_total 9000
telemt_handshake_timeouts_total 29343
telemt_upstream_connect_attempt_total 19139
telemt_upstream_connect_success_total 19110
telemt_upstream_connect_fail_total 29
telemt_upstream_connect_attempts_per_request{bucket="1"} 19139
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10134
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8900
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 76
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 29
telemt_me_keepalive_timeout_total 3363
telemt_me_reconnect_attempts_total 13815
telemt_me_reconnect_success_total 13730
telemt_me_reader_eof_total 14591
telemt_me_idle_close_by_peer_total 14591
telemt_me_route_drop_no_conn_total 221547
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 625711
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2747
telemt_desync_full_logged_total 839
telemt_desync_suppressed_total 1908
telemt_desync_frames_bucket_total{bucket="1_2"} 1102
telemt_desync_frames_bucket_total{bucket="3_10"} 900
telemt_desync_frames_bucket_total{bucket="gt_10"} 745
telemt_pool_swap_total 73
telemt_me_writer_removed_unexpected_total 13874
telemt_me_writer_restored_same_endpoint_total 13721
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 144
telemt_user_connections_total{user="hello"} 627591
telemt_user_connections_current{user="hello"} 561
telemt_user_octets_from_client{user="hello"} 9554687920 (8.90 GB)
telemt_user_octets_to_client{user="hello"} 236302261319 (220.07 GB)
telemt_user_msgs_from_client{user="hello"} 6476
telemt_user_msgs_to_client{user="hello"} 18854
telemt_user_unique_ips_current{user="hello"} 155
telemt_user_unique_ips_recent_window{user="hello"} 82
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 74688.4 (20h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1442043
telemt_connections_bad_total 6984
telemt_handshake_timeouts_total 100144
telemt_upstream_connect_attempt_total 17764
telemt_upstream_connect_success_total 17759
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 17764
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9549
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8138
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 67
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 1174
telemt_me_reconnect_attempts_total 14908
telemt_me_reconnect_success_total 13664
telemt_me_reader_eof_total 14399
telemt_me_idle_close_by_peer_total 14398
telemt_me_route_drop_no_conn_total 474144
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1100515
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4656
telemt_desync_full_logged_total 1437
telemt_desync_suppressed_total 3219
telemt_desync_frames_bucket_total{bucket="1_2"} 723
telemt_desync_frames_bucket_total{bucket="3_10"} 1687
telemt_desync_frames_bucket_total{bucket="gt_10"} 2246
telemt_pool_swap_total 65
telemt_me_writer_removed_unexpected_total 13786
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 13623
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 122
telemt_user_connections_total{user="hello"} 1100377
telemt_user_connections_current{user="hello"} 877
telemt_user_octets_from_client{user="hello"} 16521818732 (15.39 GB)
telemt_user_octets_to_client{user="hello"} 401371785705 (373.81 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 259
telemt_user_unique_ips_recent_window{user="hello"} 124
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 74689.0 (20h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 877428
telemt_connections_bad_total 12034
telemt_handshake_timeouts_total 65281
telemt_upstream_connect_attempt_total 19368
telemt_upstream_connect_success_total 19292
telemt_upstream_connect_fail_total 76
telemt_upstream_connect_attempts_per_request{bucket="1"} 19368
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10853
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8426
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 76
telemt_me_keepalive_timeout_total 1626
telemt_me_reconnect_attempts_total 23287
telemt_me_reconnect_success_total 15564
telemt_me_reader_eof_total 16622
telemt_me_idle_close_by_peer_total 16622
telemt_me_route_drop_no_conn_total 307814
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 758292
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1735
telemt_desync_full_logged_total 581
telemt_desync_suppressed_total 1154
telemt_desync_frames_bucket_total{bucket="1_2"} 487
telemt_desync_frames_bucket_total{bucket="3_10"} 674
telemt_desync_frames_bucket_total{bucket="gt_10"} 574
telemt_pool_swap_total 59
telemt_me_writer_removed_unexpected_total 15931
telemt_me_refill_failed_total 239
telemt_me_writer_restored_same_endpoint_total 15543
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_me_writer_removed_unexpected_minus_restored_total 367
telemt_user_connections_total{user="hello"} 757706
telemt_user_connections_current{user="hello"} 578
telemt_user_octets_from_client{user="hello"} 9248374016 (8.61 GB)
telemt_user_octets_to_client{user="hello"} 306912887028 (285.83 GB)
telemt_user_unique_ips_current{user="hello"} 185
telemt_user_unique_ips_recent_window{user="hello"} 82
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 74688.6 (20h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 983014
telemt_connections_bad_total 11436
telemt_handshake_timeouts_total 8126
telemt_upstream_connect_attempt_total 23502
telemt_upstream_connect_success_total 23223
telemt_upstream_connect_fail_total 279
telemt_upstream_connect_attempts_per_request{bucket="1"} 23502
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11892
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11204
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 119
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 279
telemt_me_keepalive_timeout_total 1379
telemt_me_reconnect_attempts_total 30511
telemt_me_reconnect_success_total 19477
telemt_me_reader_eof_total 20470
telemt_me_idle_close_by_peer_total 20470
telemt_me_seq_mismatch_total 33
telemt_me_route_drop_no_conn_total 365325
telemt_me_route_drop_channel_closed_total 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 902458
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 37
telemt_me_hardswap_pending_ttl_expired_total 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 3466
telemt_desync_full_logged_total 1197
telemt_desync_suppressed_total 2269
telemt_desync_frames_bucket_total{bucket="1_2"} 972
telemt_desync_frames_bucket_total{bucket="3_10"} 1167
telemt_desync_frames_bucket_total{bucket="gt_10"} 1327
telemt_pool_swap_total 34
telemt_me_writer_removed_unexpected_total 20041
telemt_me_refill_failed_total 342
telemt_me_writer_restored_same_endpoint_total 19433
telemt_me_writer_restored_fallback_total 44
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 564
telemt_user_connections_total{user="hello"} 902336
telemt_user_connections_current{user="hello"} 764
telemt_user_octets_from_client{user="hello"} 11125022416 (10.36 GB)
telemt_user_octets_to_client{user="hello"} 296680616640 (276.31 GB)
telemt_user_unique_ips_current{user="hello"} 209
telemt_user_unique_ips_recent_window{user="hello"} 105
```